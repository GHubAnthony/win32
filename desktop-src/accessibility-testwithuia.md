---
Description: Overview of how to use UI Automation and other tools to test your apps.
title: Testing with UI Automation and other tools
ms.topic: article
ms.date: 04/18/2019
---

# Testing with UI Automation and other tools

Testing the accessibility of your Windows applications, assistive technology tools, and UI frameworks is a critical step in ensuring successful user experiences for people with various disabilities, as well as users who just prefer using a keyboard.

Without adequate access, many users of assistive technology, such as screen reader and on-screen keyboard users, would be unable to use your application. It is important to thoroughly test your application to ensure that it provides adequate information about its UI elements, and that all of your application scenarios can be accomplished with just a keyboard.

This section describes tools for testing the accessibility implementation of your application to ensure that the UI is fully accessible to client applications, people with vision, learning, dexterity/mobility, and language/communication disabilities or limitations, and users who just prefer using the keyboard. It describes tools such as Inspect, AccEvent, and Keros for testing Microsoft UI Automation (UIA) and Microsoft Active Accessibility (MSAA) implementations.

## In this section

- [UI Automation for Win32](https://docs.microsoft.com/windows/desktop/winauto/entry-uiauto-win32)
- [UI Automation for .NET Framework](https://docs.microsoft.com/dotnet/framework/ui-automation/ui-automation-overview)
- [Ease of Access Assistive Technology Registration](https://docs.microsoft.com/windows/desktop/winauto/ease-of-access---assistive-technology-registration)
- [Magnification API](https://docs.microsoft.com/previous-versions/windows/desktop/magapi/entry-magapi-sdk)
- [Color and theme \***LINK**\*](???)
- [Hearing \***LINK**\*](???)


- [Inspect](https://docs.microsoft.com/windows/desktop/winauto/inspect-objects): Lets you view the accessibility data of any UI element. It is especially useful for ensuring properties and control patterns are set correctly when extending a common control or creating a custom control.
- [Accessible Event Watcher (AccEvent)](https://docs.microsoft.com/windows/desktop/winauto/accessible-event-watcher): Examines accessibility data to validate application UI elements and ensure UI elements raise proper Microsoft Active Accessibility and UI Automation events on UI events. AccEvent is typically used to debug issues and to validate that custom and extended controls are working correctly.
- [AccScope](https://docs.microsoft.com/windows/desktop/winauto/accscope): Enables visual evaluation of an application's accessibility during the early design and development phases. AccScope helps visualize how a screen reader uses UI Automation information provided by an app, and shows where adding information or support to your application can improve its accessibility.
- [UI Accessibility Checker](https://docs.microsoft.com/windows/desktop/winauto/ui-accessibility-checker): Verifies that key UI accessibility requirements in an application are achieved. AccChecker includes verification checks for UI Automation, Microsoft Active Accessibility, and Accessible Rich Internet Applications (ARIA). It can provide a static check for errors such as missing names, tree issues and more. It helps verify programmatic access and includes advanced features for automating accessibility testing.
- [UI Automation Verify](https://docs.microsoft.com/windows/desktop/winauto/ui-automation-verify): A framework for manual and automated testing of the UI Automation implementation in a control or application (results can be logged). You can integrate your application into the test code and conduct regular, automated testing or spot checks of your UI Automation scenarios. This tool is useful for verifying that changes to applications with established features do not have new issues or regressions in areas beyond the new features.