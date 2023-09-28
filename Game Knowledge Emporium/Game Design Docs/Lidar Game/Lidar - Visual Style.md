## Visual considerations

- Style that is easy to make 3d models
- Should work around the limitations
- Shadows, light, and darkness are very important to a game like this

- Subtractive charcoal drawing
- Grain texture for screen is applied
- This will be the “threshold” of force needed from each pixel to be applied to the screen
- If threshold is reached draw pixel if not draw white
- Use hatching for ocular occlusion
- Use lines or subtraction if area is too dark to create outline for objects in focus
- Use blending for everything outside depth of field (separate pass)
- Get area around objects do a distance transform and use “subtraction” to make objects stand out more

Step by step

1. Basic outline / contour / edge detection shader
2. Apply paper grain noise which will change every X seconds
3. Use depth of field to find areas in focus
4. In focus areas use distance of pixels from edges to subtract some colour around an object
5. Objects out of focus get smudged depending on their distance 
6. Use hashing texture for ocular occlusion

## Visuals references
![](https://lh3.googleusercontent.com/VvrScGTth28C1h0XwVngwxjYj2D6aUnlmAPaydFA4u5lQz83JBm49Pn-pnthMPIsk4Rg2X67oacaAeHehAxG-CmhRh_4uH_W-CTB3XTjJQRvbzv0SQCjIVZEdmvftcT2ey1Tmo59Pzwvs3J6v_Jcgs8)

![](https://lh6.googleusercontent.com/GnI2DbWJ5LQ1G302KSIyIANYOo7nTn2uJwyIicCZzazUROkaJPwITdcIfuQe4OtpCsbE97eOekK7bkQweWDq4XxOAhRgKMnZXD5mgcK-pu3sHjFIw-OYdzOkO5mKchxVStcxFfUyODQ2l3iC25lLYCY)

![](https://lh4.googleusercontent.com/dgllNL2NiMGRgNPAEqKBJBI1QtUrVas5bP6apJ7o1S0_NUdCWKGiY0lXALc9arPUzP3AX4P5hwIl3BHoc43TO2gysdQEQQOmPKr3ItrZgW-PqYlxFLBpp9Ms6gS0rW4w_fFG9i8Jjtspty6hZ-V3H6U)
