# 2FA - Two Factor Authentication

- [Introduction](#introduction)
- [Enable](#enable)

<a name="introduction"></a>
## Introduction

`2FA` is implemented to better protect both a `user's` credentials and the resources the user can access. `Two factor authentication` provides a higher level of security than authentication methods that depend on `single-factor authentication` (SFA), in which the user provides only one factor -- typically, a password or passcode. `Two factor authentication` methods rely on a user providing a password as the first factor and a second, different factor -- usually either a security token or a biometric factor, such as a fingerprint or facial scan.

`Two factor authentication` adds an additional layer of security to the authentication process by making it harder for attackers to gain access to a person's devices or online accounts because, even if the victim's password is hacked, a password alone is not enough to pass the authentication check.

Application security features are accessed by the user using the top-right user profile navigation dropdown menu. Allow the user to enable and manage two-factor authentication for their account.

When a user enables two-factor authentication for their account, they should scan the given QR code using a free TOTP authenticator application such as Google Authenticator. In addition, they should store the listed recovery codes in a secure password manager such as 1Password.

<a name="enable"></a>
## Enable Two factor authentication

All you have to do is press the `Enable` button, then a pop-up will appear where you have to confirm the password.

![Enable 2FA](https://raw.githubusercontent.com/planlify/docs/main/preview/2fa.jpg)

If you already have the Google Authenticator application on your phone, scan the QR code and enter the code of 6 dignits to complete activation.

![QR 2FA](https://raw.githubusercontent.com/planlify/docs/main/preview/2faQR.jpg)

Store these recovery codes in a secure password manager. They can be used to recover access to your account if your two factor authentication device is lost.
