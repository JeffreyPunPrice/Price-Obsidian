## extendTestOnePage
> For case [extendTestOnePage](fixtureShared.md#extendTestOnePage)([HomePage](HomePage#HomePage)), it create *PageOneClass* as a new **HomePage**
> and return the original test from playwright to extend the *PageOneClass*
> 
> Anyway, use *page1* as normal *page* (I think)
> and use *logger* without thinking
> **loggerFixture** will do the setups and finishes as a Fixture

## 
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
