# How to Modify Styles

There are various options available to modify styles in Real Homes Theme. These options gives you control over default colors as well as styles throughout the theme.

## Styles Settings

Go to **Dashboard → Real Homes → Customize Settings → Styles** for all styles related options.

![RealHomes Documentation](images/customize-theme/styles-options.png) 

## Override Default Styles

Make sure that you have selected **My Own Custom Colors** in **Dashboard → Real Homes → Customize Settings → Styles → Default or Custom** section to override the default styles and colors of the design.

<iframe width="688" height="387" src="https://www.youtube.com/embed/qjAgcc2R09k" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## Additional CSS

**Additional CSS** - Go to **Dashboard → Real Homes → Customize Settings** and click on **Additional CSS** to add any CSS code. 

![RealHomes Documentation](images/customize-theme/customize-4.png)

## Custom CSS in Child Theme

The `realhomes-child/css/child-custom.css` file is provided in child theme to add major css changes.

![RealHomes Documentation](images/customize-theme/custom-css-child.png)

!!! note
    It is highly recommended to use child theme for any changes that you want to make as this way you can update parent theme whenever an update becomes available. Simply copy a template file that you want to change to child theme after creating same directory structure and then modify it. For more info http://codex.wordpress.org/Child_Themes.

## Custom CSS in Parent Theme

If you are not using child theme then you can use **custom.css** file of the parent theme for **Classic** and **Modern** design variations separately.

If you are using *Classic* design variation **custom.css** file  path would be `realhomes/assets/classic/css/custom.css` 

![RealHomes Documentation](images/customize-theme/custom-css-classic.png)

And if you are using **Modern** design variation then **custom.css** file path would be `realhomes/assets/modern/css/custom.css`

![RealHomes Documentation](images/customize-theme/custom-css-modern.png)

## Use Child Theme for Customization ( Highly Recommended )

> It is highly recommended to use child theme for any customization that you want to make, So that you can easily update parent theme whenever a new update becomes available. A pre-built ready to use child theme is included in the main theme pack that you have downloaded from themeforest.

