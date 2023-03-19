# smart_cards

> https://docs.oracle.com/javacard/3.0.5/guide/introduction.htm#JCUGC111

> https://github.com/ph4r05/javacard-gradle-template/blob/master/applet/src/main/java/applet/HelloWorldApplet.java

> https://www.amazon.ca/Java-Card%C2%BF-Technology-Smart-Cards/dp/0201703297

> https://docs.oracle.com/en/java/javacard/3.1/guide/creating-applet-that-can-send-and-receive-extended-length-apdus.html#GUID-EE7E0160-EE8E-454D-A2F4-B706B76426FB

> https://github.com/makinako/OpenFIPS201/blob/master/src/com/makina/security/openfips201/OpenFIPS201.java

> https://www.reddit.com/r/NFC/comments/116c48b/getting_started_with_javacard/

> https://help.gototags.com/article/ferrite/

A card you buy will likely be JC 3.0.4 or 3.0.5. Most of this is relevant, though you will likely use different tooling.

For the APDUs themselves, industry by and large uses ISO7816-4 to talk to cards when we can. It makes it easier on others and provides ways to manage a filesystem

EMV Academy - This online community is dedicated to EMV education and provides a forum for professionals to discuss EMV programming and other related topics.

LinkedIn Groups - There are several LinkedIn groups focused on EMV programming and related topics, including EMV Programmers and Smart Card Security.

Reddit - There are several subreddits on Reddit that focus on EMV programming and related topics, including r/EMV, r/SmartCards, and r/CreditCardHacking.

## other secure element platforms

>   GlobalPlatform: This is an open standard for secure smart card technology that enables the development and deployment of secure applications on smart cards and other secure devices.

>   Multos: This is a high-security smart card operating system that is designed to support multiple applications on a single smart card.

>   Mifare: This is a contactless smart card technology that is widely used in transportation systems and access control applications.

>  SIM cards: These are secure platform microcontrollers that are used in mobile phones and other mobile devices.

> eSE (embedded Secure Element): This is a secure microcontroller that is integrated into a device (e.g., smartphone) to provide secure storage and processing of sensitive data.

## Card Personalisation

The Java applet on an EMV payment card runs in a secure execution environment called the Java Card Virtual Machine (JCVM). The JCVM is a lightweight virtual machine that is specifically designed for use in smart cards and other small embedded devices.

Yes, there are open source implementations of JCVM available. One example is the GlobalPlatform-compliant open source implementation of JCVM called GlobalPlatform Pro

One example of an open-source firmware image for smart cards is the Java Card OpenPlatform (JCOP) firmware
