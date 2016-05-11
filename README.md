# My customized CodeIgniter
## CI version: 3.0.4
## Implements:
1. core controller class `MY_Controller`
	- getRequest()
	- responseJson()
	- redirect()
	- render()
	- renderWithoutLayout()
	- registerCssFile()
	- registerScriptFile()
	- getPageTitle()
	- setPageTitle()
	- getPageDescription()
	- setPageDescription()
	- getPageKeywords()
	- setPageKeywords()
	- getLayout()
	- setLayout()
	- createUrl()
	- show404()
2. core model class `MY_Model`
	- getTableName()
	- getPrimaryKey()
	- getAttributes()
	- find()
	- findByPk()
	- findByAttributes()
	- findAllByAttributes()
	- _select()
	- _where()
	- _groupby()
	- _orderby()
	- _limit()
	- _getAll()
	- _getRow()
	- findAll()
	- insert()
	- insertBatch()
	- updateByPk()
	- updateAll()
	- replace()
	- deleteAll()
	- deleteByPk()
	- count()
	- countByPk()
	- max()
	- min()
	- sum()
	- avg()
	- increase()
	- decrease()
	- query()
	- queryAll()
	- transBegin()
	- transCommit()
	- transRollback()
	- transStatus()
3. core router class `MY_Router`: support controller class name format "XxxController" and action name format "actionYyy"
4. core output class `MY_Output`: support output JSON string
5. library: `Request`, `AbstractUserIdentity`,`AdminUserIdentity`
6. views: split layout from view, keep layout in folder `layouts`.
