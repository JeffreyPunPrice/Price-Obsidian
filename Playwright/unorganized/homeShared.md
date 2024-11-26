## testLogin
input
({
	 *logger*: **PriceLogger** ⇒ `testLoginBase`
	 *testInfo*: **TestInfo** ⇒ `testLoginBase`
	 *uiPage*: **HomePage** ⇒ `testLoginBase`
	 *langCode*: **LangCode** ⇒ `testLoginBase`
	 *loginType*: **LoginType** ⇒ `testLoginBase`, *uiPage.login()* ⇒ `testLoginBase`
	 *info*: **LoginInfoType**\<LoginType\> ⇒ `testLoginBase`, *uiPage.login()* ⇒ `testLoginBase`
	 *expected* : { 
		 *locator*: **string**;
		 *expectedString*: **string**;
	 } = null ⇒ `testLoginBase`
})

return Promise\<IFailed\[\]\>

[testLoginBase](testLoginBase.md)
[uiPage.login](HomePage.md#login)

## testLoginBase
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
[uiPage.visit]
[uiPage.switchLang]
[ui.Page.dismissCookieConsent]
[logger.info]
[logger.error]
[logger.finish]

## test
> created by [extendTestOnePage](fixtureShared.md#extendTestOnePage)([HomePage](HomePage.md#HomePage))
> 
> test normally will have these (I think)
>- logger
>- context ( not sure this )
>- page1
>- isMsite
>  
>  but need to pay attention if they use `extendTestTwoPage` or more, 
>  there will be not only *page1* but *page2*, *page3* etc
>  
>  just how comes the *testInfo* is still uncleared