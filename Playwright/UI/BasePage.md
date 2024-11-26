## log

- info
- error
- warn
- debug
- verbose
- customTable

## login
({
	*loginType*: **LoginType**
	*info*: **LoginInfoType\<LoginType\>**
})

return Promise\<void\>

> Switches case to call
> - [this.emailLogin](#emailLogin)
> - [this.googleLogin]
> - [this.facebookLogin]
> - [this.appleLogin]

## emailLogin
({
	*info*: **EmailInfo** ⇒ `this.performLogin`
})

[this.performLogin](#performLogin)

## performLogin
({
	*info*: **LoginParams** ⇒ `this.validateUsername`, `this.log.debug`, `this.navigateToLoginPage`
	*selector*: **LoginLocators** ⇒ `this.clickLocator`
})

> Click a bunch of locators and fill in user password

[this.validateUsername](#validateUsername)
[this.log.debug](#log)
[this.navigateToLoginPage](#navigateToLoginPage)

## validateUsername
({
	*username*: **string**
})

> Just throw error if *username* is **NULL**

## navigateToLoginPage
({
	*url*: **string** | **null** = null
})
