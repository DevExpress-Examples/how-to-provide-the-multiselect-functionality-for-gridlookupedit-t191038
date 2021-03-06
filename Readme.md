<!-- default file list -->
*Files to look at*:

* [Customer.cs](./CS/Customer.cs) (VB: [Customer.vb](./VB/Customer.vb))
* **[Form1.cs](./CS/Form1.cs) (VB: [Form1.vb](./VB/Form1.vb))**
* [Program.cs](./CS/Program.cs) (VB: [Program.vb](./VB/Program.vb))
<!-- default file list end -->
# How to provide the MultiSelect functionality for GridLookUpEdit


A general idea is to use <a href="https://documentation.devexpress.com/#WindowsForms/clsDevExpressXtraEditorsPopupContainerEdittopic">PopupContainerEdit</a> with a <a href="https://documentation.devexpress.com/#WindowsForms/clsDevExpressXtraGridGridControltopic">GridControl</a> inside. In this example, an editor's value is represented by CSV. So, you can type in textbox comma-separated values from the popup, and they will be automatically selected. And vice versa, when you select values in the popup and close it, the selected values will appear as a comma-separated string.<br />


<b>See also:</b>

[DevExpress WinForms Troubleshooting - LookUp Editors](https://go.devexpress.com/CheatSheets_WinForms_Examples_T929986.aspx)

<br/>


