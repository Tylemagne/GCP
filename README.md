# Unity is yours
Have you ever wanted to have a tremendous amount of realtime control over Unity3D's inner intricacies in your project without having to write it the code yourself? Look no further.

# Instructions

1. Create an empty gameobject
2. Attach GMCP
3. Press Play and use the assigned trigger key to pull up GMCP


# How it works

1. GCP initializes and renames its parent gameObject
2. GCP waits for input (the button varies per script variant)
3. If GCP's input trigger is triggered, the GCP window will be generated
4. The window handles all setting changes and directly alters Unity engine variables in realtime
