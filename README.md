# DIY-CommunityNet

Building a do-it-yourself HowTo for building a small local wifi network with services.


## **Mission**

I live in an apartment complex with a lot of families. With the current stay-at-home conditions, I want to repurpose my spare equipment into a local wifi network with some services set up.

## **Services**

#### **Needs:**
* Has video streaming that's as simple as possible to use [probably JellyFin]
* Has a social media (likely just a community board) to encourage mutual aid networking... a hi-tech way to ask to borrow a cup of sugar [so far OSSN is top prospect]
* Managed DNS/DHCP so clients are routed *only* to the service pages [probably PiHole]

#### **Wants:**
* Has a captive portal 'sign-in' page to associate devices to neighbors in case of abuse.

## Network
Basic network layout
```
[Router](PiHole)
[Access Point] -- [repeaters]
|      |
video  Community
```
Not complex, but with cheap consumer equipment not easy to scale. We shall do what we can.
