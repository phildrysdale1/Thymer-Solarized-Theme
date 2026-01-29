# Thymer-Solarized-Theme
These themes are designed for the Thymer notes application. Designed around the [Solarized colour palette](https://ethanschoonover.com/solarized/).
They still need work in less obvious spots... and also with the horrible banner gradient, which I don't think we can change right now.
If you add any areas I've missed please do submit a PR or tag me in the Discord themes channel and I'll add the changes :)

## How to apply:
1. Open the desired theme CSS file in this repository and copy (Ctrl + C) all of its contents.
2. Open up Thymer. Press Ctrl + P > Edit Theme CSS > paste (Ctrl + V) > Click Save.
3. Press Ctrl + P again > Set Theme > Select the theme
   
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
<img width="1708" height="1371" alt="image" src="https://github.com/user-attachments/assets/bc76221c-684f-4862-8b63-aba3eff35884" />

### Solarized Dark
<img width="1707" height="1370" alt="image" src="https://github.com/user-attachments/assets/090c40c2-99aa-4a74-bef2-8b7c5a051ca7" />

