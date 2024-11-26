input
({
	 logger: PriceLogger,
	 testInfo: TestInfo,
	 uiPage: HomePage,
	 langCode: LangCode,
	 loginType: LoginType,
	 info: LoginInfoType\<LoginType\>,
	 expected: {
	   locator: string;
	   expectedString: string;
	 } = null
})

return Promise\<IFailed\[\]\>