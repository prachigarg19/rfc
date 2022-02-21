# Intelligent Autozoom Camera

- Proposal By: @2002Bishwajeet
- Start Date: 03-04-2022
- Target Date:  31-07-2022 (expected)

## Summary

A Flutter app that lets you take pictures of anything and autozooms to the right size to pick up an object that is in view. For example: Take a collection of dogs, or cats (there are probably pretrained models for this, it's up to you to look them up). If your app is used to take a picture of a dog, then the zoom should be automatically adjusted to take a picture of the dog in foreground, even if the dog is a bit far.

It must be fast or the dog will move!

## Problem Statement (Step 1)

[problem-statement]: #problem-statement

**What problem are you trying to solve?**

It doesn't solve any problems right now(it maybe but we may know not about it yet). Our main purpose to work on this Project is to learn how to work with complex state management stuffs in Flutter and make a camera app that can be used to take pictures of anything and autozooms to the right size to pick up an object that is in view.

## Design proposal (Step 2)

[design-proposal]: #design-proposal

We will be dividing the proposal into three phases:

### First Phase

This will be the inital phase. We will be working on mainly UI/UX and state management stuffs. Since the app will be cross platform, we will try to make it minimalistic for both android and IOs.

After the implementation of UI, we will integrating the `camera_plugins` in our app. We will be dealing mainly with getting the realtime data from the camera and capture stuffs.

### Second Phase

This will be the backend phase. Since our app is auto-zooming on the object, it deals with Machine learning and stuffs or some pretrained models. This would require some extensive research. After that all we need is to connect those APIs and we should be good to go.

<!--
This is the technical portion of the RFC. Explain the design in sufficient detail, keeping in mind the following:

- Its interaction with other parts of the system is clear
- It is reasonably clear how the contribution would be implemented
- Dependencies on libraries, tools, projects, or work that isn't yet complete
- New API routes that need to be created or modifications to the existing routes (if needed)
- Any breaking changes and ways in which we can ensure backward compatibility.
- Use Cases
- Goals
- Deliverables
- Changes to documentation
- Ways to scale the solution

Ensure that you include examples and code snippets to allow the community to understand the proposed solution. **It would be best if the examples use naming conventions that you intend to use during the actual implementation to suggest changes early on during the development.**

Write your answer below.

-->

### Supporting Libraries

<!--
Which different libraries do we need to support the new features?
Please describe the new library's potential API?
Avoid using 3rd party libraries when possible, if required - explain why.
-->

### Reliability (Tests & Benchmarks)

#### Scaling

Since, this would be a standalone app, I don't think we need to scale it. If it involves backend server works, then I will add the scaling planning here.

#### Benchmarks

Our Benchmarks should mainly focus on how accurate and fast object detection takes place. Will reveal about this soon.

#### Tests (UI, Unit, E2E)

This time we would focus on writing unit tests so as to get introduced on how to write tests in Flutter.

### Documentation & Content

For Documentation, we could explain how to use the app and how to use the camera. In short just a live working on how the app works.

### Prior art

[prior-art]: #prior-art

N/A

### Unresolved questions

[unresolved-questions]: #unresolved-questions

There are lots of questions that we have not yet answered. For example I don't know how it will work actually. How the camera zooms automatically. It has do something with Machine learning but it requires quite a bit research.

This will be updated soon.

### Future possibilities

[future-possibilities]: #future-possibilities

The inital MVP will be involved for auto-zooming and capturing the image. This can be further scaled to record videos and stuffs for a particular object.
Let's say, we want to capture a dog running in the park and it should zoom it to it or something like that.
