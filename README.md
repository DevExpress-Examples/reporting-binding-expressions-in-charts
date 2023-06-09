<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/642266728/2023.1)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/T1166846)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->

# Reporting for WinForms - Display Average Values in Charts

The following example displays a constant line that shows average product prices in each category.

![XRCharts](Images/xrchart.png)

In this example, the constant line is bound to the following expression:

```expression
[CategoriesProducts].Avg([UnitPrice])
```

![Expression Editor](Images/expression-editor.png)

## Documentation

* [Bind Report Controls to Data with Binding Expressions](https://docs.devexpress.com/XtraReports/1180/detailed-guide-to-devexpress-reporting/use-report-controls/bind-report-controls-to-data/specify-a-control-s-binding-expression?v=23.1)
