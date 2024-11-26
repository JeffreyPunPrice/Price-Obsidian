input
({
	 *logger*: **PriceLogger** ⇒ used here
	 *testInfo*: **TestInfo** ⇒ `caseName` ⇒ *logger*.start
	 *uiPage*: **HomePage** ⇒ used here
	 *langCode*: **LangCode** ⇒ `uiPage.switchLang`
	 *loginType*: **LoginType** ⇒ `loginFunction`
	 *info*: **LoginInfoType**\<LoginType\> ⇒ `loginFunction`
	 *loginFunction*:  **Func Promise\<void\>**
	 *expected* : { 
		 *locator*: **string**;
		 *expectedString*: **string**;
	 } = null ⇒ `expect`
	 *highlights?*: **string\[\]**
})

return Promise\<IFailed\[\]\>

### function related
[logger.start]
