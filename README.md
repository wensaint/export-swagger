# Export JSON swagger
Export swagger to Excel

Information
---
- .Net Core 2.2
- OfficeOpenXml
- Console application

Use guide
---
1. Download file swagger.json from Swagger UI
2. Put file swagger.json to folder bin/debug/netcoreapp2.2
3. Run project / Press F5
4. Your document is document.xlsx file

# folk更新说明
原作者只允许将path下第一个方法体导出，这显然不符合RESTful风格习惯，所以在此基础上进行扩展，允许将所有方法(method)导出
