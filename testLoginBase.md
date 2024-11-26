input
({
	 *logger*: **PriceLogger** ⇒ `testLoginBase`
	 *testInfo*: **TestInfo** ⇒ `testLoginBase`
	 *uiPage*: **HomePage** ⇒ `testLoginBase`
	 *langCode*: **LangCode** ⇒ `testLoginBase`
	 *loginType*: **LoginType** ⇒ `testLoginBase`, `uiPage.login` ⇒ `testLoginBase`
	 *info*: **LoginInfoType**\<LoginType\> ⇒ `testLoginBase`, `uiPage.login` ⇒ `testLoginBase`
	 *loginFunction*:  **Func Promise\<void\>**
	 *expected* : { 
		 *locator*: **string**;
		 *expectedString*: **string**;
	 } = null ⇒ `testLoginBase`
})