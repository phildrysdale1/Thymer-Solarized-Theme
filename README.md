# Thymer-Solarized-Theme
These themes are designed for the Thymer notes application. Designed around the [Solarized colour palette](https://ethanschoonover.com/solarized/).
They still need work in less obvious spots... and also with the horrible banner gradient, which I don't think we can change right now.
If you add any areas I've missed please do submit a PR or tag me in the Discord themes channel and I'll add the changes :)

# Contents
  - Thymer Solarized Light CSS
  - Thymer Solarized Dark CSS


## How to apply:
1. Open the desired theme CSS file in this repository and copy (Ctrl + C) all of its contents.
2. Open up Thymer. Press Ctrl + P > Edit Theme CSS > paste (Ctrl + V) > Click Save.
3. Press Ctrl + P again > Set Theme > Catppuccin Latte.

### Fixing the banner gradient
While far from a perfect fix (I'm on it)
You can remove the gradient from the banner by adding the following to the edit theme CSS section in Thymer. 
```
html[data-theme] {
  .banner-outer {
    visibility: hidden;
  }
}
```

### Solarized Light
<img width="1541" height="1235" alt="image" src="https://github.com/user-attachments/assets/3dc916ab-9499-4537-aa2f-501e4f298f56" />


### Solarized Dark
<img width="1544" height="1238" alt="image" src="https://github.com/user-attachments/assets/e6d2047f-9498-48ae-b60f-39e6d8d5b3ab" />


