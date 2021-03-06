# UX design patterns for Office Add-ins. 

This repository provides sample implementations in HTML and CSS of common UX design patterns for Office Add-ins.

When designing Office Add-ins, the UX design of your add-in should provide compelling experiences that extend Office. To create a great add-in, your add-in should provide a first-run experience, a first-class UX experience, and smooth transitions between pages, among other things. Providing a clean, modern UX experience increases user retention and adoption of your add-in. This repo has UX resources for developers that implement:

* Common UX design patterns based on best practices.
* Office Fabric components and styles.
* Add-ins that look like a natural extension of the default Office UI. 

## How do I get started using these resources?

There are no prerequisites to use these design or code resources. To get started creating a great UX for your add-in:

* Review the UX design patterns, and identify which ones are important to your add-in. For example, pick one of the first-run experiences.
* Then do one or more of the following:
	* Copy the code files to your add-in project and start customizing them to meet your requirements. You will need the [common.js file](https://github.com/OfficeDev/Office-Add-in-UX-Design-Pattern-Code/tree/master/), the [assets folder](https://github.com/OfficeDev/Office-Add-in-UX-Design-Pattern-Code/tree/master/assets), and the code folder for the design pattern you choose. See links below.
	* Take a look at the  and use them as a guide when creating your own UX design. See links below.
	* Download the Adobe Illustrator files and edit them to mock-up your own add-in designs. Get them [here](https://github.com/OfficeDev/Office-Add-in-Design-Patterns/blob/master/Patterns/Source%20Files).

## Generic and Branding

* **Landing (or generic) page** is a standard add-in page. Users may be redirected to a landing page after a first-run experience or sign-in process. ([spec](https://github.com/OfficeDev/Office-Add-in-Design-Patterns/blob/master/Helpful%20Templates/AddIn_Template_Standard_Layout.pdf "PDF"), [code](https://github.com/OfficeDev/Office-Add-in-UX-Design-Patterns-Code/tree/master/templates/generic/landing-page))
* **Brand image in brand bar** is the landing page with an image in the footer. ([spec](https://github.com/OfficeDev/Office-Add-in-UX-Design-Patterns/blob/master/Patterns/Brand_Bar.md), [code](https://github.com/OfficeDev/Office-Add-in-UX-Design-Patterns-Code/tree/master/templates/generic/brand-bar))

<table>
 <tr><th>Landing</th><th>Brand Bar</th></tr>
 <tr><td><A href="https://github.com/OfficeDev/Office-Add-in-UX-Design-Patterns-Code/tree/master/templates/generic/landing-page"><img src="https://github.com/OfficeDev/Office-Add-in-UX-Design-Patterns-Code/blob/master/Images/landing.page.PNG" alt="landing page" style="width: 264px;"/></A></td>
<td><A href="https://github.com/OfficeDev/Office-Add-in-UX-Design-Patterns-Code/tree/master/templates/generic/brand-bar"><img src="https://github.com/OfficeDev/Office-Add-in-UX-Design-Patterns-Code/blob/master/Images/brand.bar.PNG" alt="brand bar" style="width: 264px;"/></A></td></tr>
 </table>

## First-Run

A first-run experience is the experience a user has when opening your add-in for the first time. The following lists the first run design patterns you can include in your add-in. Images of each of them are below.

* **Steps to start** provides users with an ordered list of steps to perform to get started using your add-in. ([spec](https://github.com/OfficeDev/Office-Add-in-Design-Patterns/blob/master/Patterns/FirstRun_StepsToStart.md), [code](https://github.com/OfficeDev/Office-Add-in-UX-Design-Patterns-Code/tree/master/templates/first-run/instruction-step))
* **Value** communicates your add-in's value proposition. ([spec](https://github.com/OfficeDev/Office-Add-in-Design-Patterns/blob/master/Patterns/FirstRun_ValuePlacemat.md), [code](https://github.com/OfficeDev/Office-Add-in-UX-Design-Patterns-Code/tree/master/templates/first-run/value-placemat))
* **Video** shows users a video before they start using your add-in. ([spec](https://github.com/OfficeDev/Office-Add-in-Design-Patterns/blob/master/Patterns/FirstRun_VideoPlacemat.md), [code](https://github.com/OfficeDev/Office-Add-in-UX-Design-Patterns-Code/tree/master/templates/first-run/video-placemat))
* **Walkthrough** takes users through a series of features or information before they start using the add-in. ([spec](https://github.com/OfficeDev/Office-Add-in-Design-Patterns/blob/master/Patterns/FirstRun_PagingPanel.md), [code](https://github.com/OfficeDev/Office-Add-in-UX-Design-Patterns-Code/tree/master/templates/first-run/walkthrough))
* The [Office Store](https://msdn.microsoft.com/en-us/library/office/jj220033.aspx) has a system for providing users with a trial version of an add-in, but if you want full control of the UI for a trial experience, use the following templates:
	* **Trial** shows users how to get started with a trial version of your add-in. ([spec](https://github.com/OfficeDev/Office-Add-in-Design-Patterns/blob/master/Patterns/FirstRun_TrialVersion.md), [code](https://github.com/OfficeDev/Office-Add-in-UX-Design-Patterns-Code/tree/master/templates/first-run/trial-placemat))
	* **Trial feature** advises users that the feature they are trying to use is not available in the trial version of the add-in. ([code](https://github.com/OfficeDev/Office-Add-in-UX-Design-Patterns-Code/tree/master/templates/first-run/trial-placemat-feature))


> Note: Consider whether showing users the first-run experience once or many times is important to your scenario. For example, if users use your add-in periodically, they may forget how to use the add-in. Seeing the first-run experience again may be helpful to those users. 

 <table>
 <tr><th>Steps to Start</th><th>Value</th><th>Video</th></tr>
 <tr>
<td><A href="https://github.com/OfficeDev/Office-Add-in-UX-Design-Patterns-Code/tree/master/templates/first-run/instruction-step"><img src="https://github.com/OfficeDev/Office-Add-in-UX-Design-Patterns-Code/blob/master/Images/instruction.step.PNG" alt="instruction steps" style="width: 264px;"/></A></td>
<td><A href="https://github.com/OfficeDev/Office-Add-in-UX-Design-Patterns-Code/tree/master/templates/first-run/value-placemat"><img src="https://github.com/OfficeDev/Office-Add-in-UX-Design-Patterns-Code/blob/master/Images/value.placemat.PNG" alt="value placemat" style="width: 264px;"/></A></td>
<td><A href="https://github.com/OfficeDev/Office-Add-in-UX-Design-Patterns-Code/tree/master/templates/first-run/video-placemat"><img src="https://github.com/OfficeDev/Office-Add-in-UX-Design-Patterns-Code/blob/master/Images/video.placemat.PNG" alt="video placemat" style="width: 264px;"/></A></td></tr>
 </table>

 <table>
 <tr><th>Walkthrough first page</th><th>Trial</th><th>Trial feature</th></tr>
 <tr>
<td><A href="https://github.com/OfficeDev/Office-Add-in-UX-Design-Patterns-Code/tree/master/templates/first-run/walkthrough"><img src="https://github.com/OfficeDev/Office-Add-in-UX-Design-Patterns-Code/blob/master/Images/walkthrough1.PNG" alt="walkthrough 1" style="width: 264px;"/></A></td>
<td><A href="https://github.com/OfficeDev/Office-Add-in-UX-Design-Patterns-Code/tree/master/templates/first-run/trial-placemat"><img src="https://github.com/OfficeDev/Office-Add-in-UX-Design-Patterns-Code/blob/master/Images/trial.placemat.PNG" alt="trial placemat" style="width: 264px;"/></A></td>
<td><A href="https://github.com/OfficeDev/Office-Add-in-UX-Design-Patterns-Code/tree/master/templates/first-run/trial-placemat-feature"><img src="https://github.com/OfficeDev/Office-Add-in-UX-Design-Patterns-Code/blob/master/Images/trial.placemat.feature.PNG" alt="trial placemat feature" style="width: 264px;"/></A></td></tr>
 </table> 

## Notifications

There are a variety of ways that your add-in can notify users of events, such as errors, or of progress. The following lists these techniques. Images of each of them are below.

* **Embedded dialog**  shows a dialog inside the task pane that provides information and, optionally, an interactive experience, using buttons or other controls. Consider using one to prompt a user to confirm an action. ([spec](https://github.com/OfficeDev/Office-Add-in-Design-Patterns/blob/master/Patterns/Embedded_Dialog.md) , [code](https://github.com/OfficeDev/Office-Add-in-UX-Design-Patterns-Code/tree/master/templates/notifications/embedded-dialog))
* **Inline message** indicates error, success, or information, and it can appear at a specified location in the task pane. For example, if a user enters an improperly formatted email address in a text box, an error message appears just below the text box. ([spec](https://github.com/OfficeDev/Office-Add-in-Design-Patterns/blob/master/Patterns/Notification_Inline_Message.md), [code](https://github.com/OfficeDev/Office-Add-in-UX-Design-Patterns-Code/tree/master/templates/notifications/inline-message))
* **Message banner** provides information and, optionally, a simple call to action, in a banner that can be collapsed to a single line, expanded to multiple lines, or dismissed. Consider using message banners to report a service update or a helpful tip when the add-in starts. ([spec](https://github.com/OfficeDev/Office-Add-in-UX-Design-Patterns/blob/master/Patterns/Notification_MessageBanner.md), [code](https://github.com/OfficeDev/Office-Add-in-UX-Design-Patterns-Code/tree/master/templates/notifications/message-banner))
* **Progress bar** indicates the progress of a long-running, synchronous process, such as a configuration task that must complete before the user can take any further action. It is a separate interstitial page that also reinforces the add-in brand. Use a progress bar when the process can send periodic measures of how far along it is back to the add-in. ([spec](https://github.com/OfficeDev/Office-Add-in-UX-Design-Patterns/blob/master/Patterns/Notification_Progress.md), [code](https://github.com/OfficeDev/Office-Add-in-UX-Design-Patterns-Code/tree/master/templates/notifications/progress-bar))
* **Spinner** indicates that a long-running, synchronous process is underway, but provides no indication of how far along it is. It is a separate interstitial page that also reinforces the add-in brand. Use a spinner when the add-in cannot know reliably how far along a process is. ([spec](https://github.com/OfficeDev/Office-Add-in-UX-Design-Patterns/blob/master/Patterns/Notification_Progress.md), [code](https://github.com/OfficeDev/Office-Add-in-UX-Design-Patterns-Code/tree/master/templates/notifications/spinner))
* **Toast** provides a brief message that fades away after a few seconds. Since the user might not see the message, use toast only for inessential information. It is a good choice for notifying users of an event in a remote system, such as the receipt of an email. ([spec](https://github.com/OfficeDev/Office-Add-in-UX-Design-Patterns/blob/master/Patterns/Notification_Toast.md), [code](https://github.com/OfficeDev/Office-Add-in-UX-Design-Patterns-Code/tree/master/templates/notifications/toast))

 <table>
 <tr><th>Embedded dialog</th><th>Inline message</th><th>Message banner</th></tr>
 <tr><td><A href="https://github.com/OfficeDev/Office-Add-in-UX-Design-Patterns-Code/tree/master/templates/notifications/embedded-dialog"><img src="https://github.com/OfficeDev/Office-Add-in-UX-Design-Patterns-Code/blob/master/Images/embedded.dialog.PNG" alt="embedded dialog" style="width: 264px;"/></A></td>
<td><A href="https://github.com/OfficeDev/Office-Add-in-UX-Design-Patterns-Code/tree/master/templates/notifications/inline-message"><img src="https://github.com/OfficeDev/Office-Add-in-UX-Design-Patterns-Code/blob/master/Images/inline.message.PNG" alt="inline message" style="width: 264px;"/></A></td>
<td><A href="https://github.com/OfficeDev/Office-Add-in-UX-Design-Patterns-Code/tree/master/templates/notifications/message-banner"><img src="https://github.com/OfficeDev/Office-Add-in-UX-Design-Patterns-Code/blob/master/Images/message.banner.PNG" alt="message banner" style="width: 264px;"/></A></td></tr>
 </table>

 <table>
 <tr><th>Progress bar</th><th>Spinner</th><th>Toast</th></tr>
 <tr><td><A href="https://github.com/OfficeDev/Office-Add-in-UX-Design-Patterns-Code/tree/master/templates/notifications/progress-bar"><img src="https://github.com/OfficeDev/Office-Add-in-UX-Design-Patterns-Code/blob/master/Images/progress.bar.PNG" alt="progress bar" style="width: 264px;"/></A></td>
<td><A href="https://github.com/OfficeDev/Office-Add-in-UX-Design-Patterns-Code/tree/master/templates/notifications/spinner"><img src="https://github.com/OfficeDev/Office-Add-in-UX-Design-Patterns-Code/blob/master/Images/spinner.PNG" alt="spinner" style="width: 264px;"/></A></td>
<td><A href="https://github.com/OfficeDev/Office-Add-in-UX-Design-Patterns-Code/tree/master/templates/notifications/toast"><img src="https://github.com/OfficeDev/Office-Add-in-UX-Design-Patterns-Code/blob/master/Images/toast.PNG" alt="toast" style="width: 264px;"/></A></td></tr>
 </table>

## Known issues

* Running some code files outside of an add-in project throws a JavaScript error. 
	* Resolution: Ensure you add these files to an Office add-in project. 
	
## Additional resources

* [Best practices for developing Office Add-ins](https://dev.office.com/docs/add-ins/design/add-in-development-best-practices)
* [Office UI Fabric](http://dev.office.com/fabric/)

Copyright (c) Microsoft Corporation 2016. All rights reserved.
