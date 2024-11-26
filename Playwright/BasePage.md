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

Switches case to call
- [this.emailLogin](#emailLogin)
- [this.googleLogin]
- [this.facebookLogin]
- [this.appleLogin]

## emailLogin
({
	*info*: **EmailInfo** ⇒ `this.performLogin`
})

[this.performLogin](#performLogin)

## performLogin
({
	*info*: **LoginParams**  `this.validateUsername`
	*selector*: **LoginLocators**
})
