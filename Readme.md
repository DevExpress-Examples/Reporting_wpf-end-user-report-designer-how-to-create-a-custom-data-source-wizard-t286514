<!-- default file list -->
*Files to look at*:

* [CusomDataSourceWizardControl.xaml](./CS/CusomDataSourceWizardControl.xaml) (VB: [CusomDataSourceWizardControl.xaml](./VB/CusomDataSourceWizardControl.xaml))
* [CusomDataSourceWizardControl.xaml.cs](./CS/CusomDataSourceWizardControl.xaml.cs) (VB: [CusomDataSourceWizardControl.xaml](./VB/CusomDataSourceWizardControl.xaml))
* [ConnectionWrapper.cs](./CS/Custom Wizard/Data Wrapper Classes/ConnectionWrapper.cs) (VB: [ConnectionWrapper.vb](./VB/Custom Wizard/Data Wrapper Classes/ConnectionWrapper.vb))
* [DataSourceWrapper.cs](./CS/Custom Wizard/Data Wrapper Classes/DataSourceWrapper.cs) (VB: [DataSourceWrapper.vb](./VB/Custom Wizard/Data Wrapper Classes/DataSourceWrapper.vb))
* [QueryWrapper.cs](./CS/Custom Wizard/Data Wrapper Classes/QueryWrapper.cs) (VB: [QueryWrapper.vb](./VB/Custom Wizard/Data Wrapper Classes/QueryWrapper.vb))
* [EditDataSourceWindow.xaml](./CS/Custom Wizard/EditDataSourceWindow.xaml) (VB: [EditDataSourceWindow.xaml](./VB/Custom Wizard/EditDataSourceWindow.xaml))
* [EditDataSourceWindow.xaml.cs](./CS/Custom Wizard/EditDataSourceWindow.xaml.cs) (VB: [EditDataSourceWindow.xaml](./VB/Custom Wizard/EditDataSourceWindow.xaml))
* [EditQueryWindow.xaml](./CS/Custom Wizard/EditQueryWindow.xaml) (VB: [EditQueryWindow.xaml](./VB/Custom Wizard/EditQueryWindow.xaml))
* [EditQueryWindow.xaml.cs](./CS/Custom Wizard/EditQueryWindow.xaml.cs) (VB: [EditQueryWindow.xaml](./VB/Custom Wizard/EditQueryWindow.xaml))
* [CustomCloseWizardEventArgs.cs](./CS/Custom Wizard/Misc/CustomCloseWizardEventArgs.cs) (VB: [CustomCloseWizardEventArgs.vb](./VB/Custom Wizard/Misc/CustomCloseWizardEventArgs.vb))
* [WizardCloseMode.cs](./CS/Custom Wizard/Misc/WizardCloseMode.cs) (VB: [WizardCloseMode.vb](./VB/Custom Wizard/Misc/WizardCloseMode.vb))
* [WizardDataModel.cs](./CS/Custom Wizard/WizardDataModel.cs) (VB: [WizardDataModel.vb](./VB/Custom Wizard/WizardDataModel.vb))
* [WizardDialog.xaml](./CS/Custom Wizard/WizardDialog.xaml) (VB: [WizardDialog.xaml.vb](./VB/Custom Wizard/WizardDialog.xaml.vb))
* [WizardDialog.xaml.cs](./CS/Custom Wizard/WizardDialog.xaml.cs) (VB: [WizardDialog.xaml.vb](./VB/Custom Wizard/WizardDialog.xaml.vb))
* [Dictionary1.xaml](./CS/Dictionary1.xaml) (VB: [Dictionary1.xaml](./VB/Dictionary1.xaml))
* **[MainWindow.xaml](./CS/MainWindow.xaml) (VB: [MainWindow.xaml](./VB/MainWindow.xaml))**
* [MainWindow.xaml.cs](./CS/MainWindow.xaml.cs) (VB: [MainWindow.xaml](./VB/MainWindow.xaml))
<!-- default file list end -->
# WPF End-User Report Designer - How to create a custom data source wizard


This example demonstrates how to create a dialog that allows end-users create a new report and customize its Data Source in the <a href="https://community.devexpress.com/blogs/thinking/archive/2015/05/20/wpf-report-designer-ctp-1-coming-soon-in-v15-1.aspx">WPF Report Designer</a>.<br><br>
<p>For an example illustrating how to customize the <a href="https://documentation.devexpress.com/#XtraReports/CustomDocument114841">existing wizard</a>, please see <a href="https://www.devexpress.com/Support/Center/Question/Details/T456882">WPF Report Designer - How to customize the Data Source wizard</a>.</p>
<br>To complete this solution, I used the DevExpress <a href="https://documentation.devexpress.com/#WPF/CustomDocument15112">MVVM Framework</a> and <a href="https://msdn.microsoft.com/en-us/library/system.componentmodel.ieditableobject.aspx">IEditableObject</a>. Here are useful links:<br><a href="https://documentation.devexpress.com/#WPF/CustomDocument15112">MVVM Framework</a> <br><a href="https://documentation.devexpress.com/#WPF/CustomDocument17352">POCO ViewModels</a> <br><a href="http://paulstovell.com/blog/editable-object-adapter">IEditableObject Adapter for WPF and Windows Forms</a> <br><br>ASP.NET: <a href="https://www.devexpress.com/Support/Center/p/T196136">ASPxReportDesigner - How to add/edit/remove DataSourses in the web report designer (Custom DataSource wizard)</a>

<br/>


