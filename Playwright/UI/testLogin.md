input
({
	 *logger*: **PriceLogger** ⇒ `testLoginBase`
	 *testInfo*: **TestInfo** ⇒ `testLoginBase`
	 *uiPage*: **HomePage** ⇒ `testLoginBase`
	 *langCode*: **LangCode** ⇒ `testLoginBase`
	 *loginType*: **LoginType** ⇒ `testLoginBase`, `uiPage.login` ⇒ `testLoginBase`
	 *info*: **LoginInfoType**\<LoginType\> ⇒ `testLoginBase`, `uiPage.login` ⇒ `testLoginBase`
	 *expected* : { 
		 *locator*: **string**;
		 *expectedString*: **string**;
	 } = null ⇒ `testLoginBase`
})

return Promise\<IFailed\[\]\>