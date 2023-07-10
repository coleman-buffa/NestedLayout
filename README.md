_Layout files can be nested in .Net Framework! This feature is helpful as it improves maintainability, creates a consistent look and feel for common pages, and allows segments of an application to have their own look and feel. The following illustrates this concept using a ficticious large tech company with multiple divisions:

`_MainLayout.cshtml` is the base layout file containing all common elements, scripts, stylesheets, and third party libraries.

`_AutomationLayout.cshtml` and `_ElectronicsLayout.cshtml` implement their own navigation bars, footers, and styling. In addition any third party libraries specific to that part of the application can go here.

Layout files can be nested as deeply as you dare.

A working version of this application can be found in [this repository](https://github.com/coleman-buffa/NestedLayout)

Credit [Mike Brind](https://www.mikesdotnetting.com/article/164/nested-layout-pages-with-razor)