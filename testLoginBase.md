input
({
	 *logger*: **PriceLogger** ⇒ 
	 *testInfo*: **TestInfo** ⇒ 
	 *uiPage*: **HomePage** ⇒ 
	 *langCode*: **LangCode** ⇒ `uiPage.switchLang`
	 *loginType*: **LoginType** ⇒ `testLoginBase`, `uiPage.login` ⇒ `testLoginBase`
	 *info*: **LoginInfoType**\<LoginType\> ⇒ `testLoginBase`, `uiPage.login` ⇒ `testLoginBase`
	 *loginFunction*:  **Func Promise\<void\>**
	 *expected* : { 
		 *locator*: **string**;
		 *expectedString*: **string**;
	 } = null ⇒ `expect`
	 *highlights?*: **string\[\]**
})

return Promise\<IFailed\[\]\>