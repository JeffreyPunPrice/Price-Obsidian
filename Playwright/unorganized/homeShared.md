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
[uiPage.login](uiPage.login.md)


## test
> created by [extendTestOnePage](fixtureShared.md#extendTestOnePage)([HomePage](HomePage#HomePage))
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