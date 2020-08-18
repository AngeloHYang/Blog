# Yes, Emails are leaking your IP address

***Last edit: 03:34:11 8/19/2020***

> The article is not for technical discussion. This is neither complete nor professional. This is for reference only.

I was going through some emails I sent to myself. I became aware of the IP address leaking problem of which you can check out the sender's IP, including the internet and local network, from the header of the email.

That's why I started a little experiment. The email providers include Outlook, Gmail, iCloud, Yandex, QQ, 163. The platforms include Outlook APP, Thunderbird, iOS Mail APP, and the Web.

Here's the result

## iOS Mail APP

Email Provider | IP Address Leaking
:---- | ----:
163 | √
QQ | √
iCloud | √
Outlook | √
Gmail | ×
Yandex | ×

## Outlook APP

Email Provider | IP Address Leaking
:---- | ----:
163 | ×
QQ | -
iCloud | ×
Outlook | ×
Gmail | -
Yandex | ×

They all came with Microsoft's IP addresses.

## Web

Email Provider | IP Address Leaking
:---- | ----:
163 | √
QQ | √
iCloud | ×
Outlook | ×
Gmail | ×
Yandex | ×

## Thunderbird

Email Provider | IP Address Leaking
:---- | ----:
163 | √
QQ | -
iCloud | √
Outlook | √
Gmail | -
Yandex | -

---

## **[⇦ Previous: Variable in Java Enhanced For Statement](https://angelohyang.github.io/Blog/Dec.%202019/Java_For_Reference_or_Copy)**

## **[🏡 Back to Home Page](https://angelohyang.github.io/Blog/)**
