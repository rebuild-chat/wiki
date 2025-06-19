---
title: "Frequently Asked Questions"
type: docs
---

# FAQs

## What is Rebuild.Chat?

Rebuild is a Matrix homeserver who believe the current state of events is beyond simple ammendment, hence "Rebuild". The topic of most rooms is how to start taking action and planning what needs to be done.

## How do I join Rebuild.Chat?

If you already have a Matrix homeserver, you are welcome to join via federation. Otherwise, you can create an account with us as your homeserver (with the option of joining other servers via federation as well).

### Creating an account

{{% tabs %}}
{{% tab "Desktop (Rebuild Web Client)" %}}
1. Open up your browser of choice to https://rebuild.chat/
2. Click "Create an account"
3. Click "Continue" to bypass the homeserver selection, and fill out the form
{{% /tab %}}

{{% tab "Mobile (and other third party Matrix clients)" %}}
1. Download the client of your choice. (I recommend [FluffyChat](https://matrix.org/ecosystem/clients/fluffychat/) but they all have their tradeoffs.)
2. Change homeserver to `rebuild.chat`
3. Click "Create Account"
{{% /tab %}}
{{% /tabs %}}

### Joining the main chat

https://matrix.to/#/#main:rebuild.chat

This link should include instructions for your specific client on how to join our main chat room.

### Joining State Spaces

{{% tabs %}}
{{% tab "Desktop (Rebuild Web Client)" %}}
1. Type the name of your state in the search bar
2. Click "Public Spaces" to search for spaces
3. Click your state's space
4. Join the channel for your metropolitan area
{{% /tab %}}

{{% tab "Mobile (and other third party Matrix clients)" %}}
{{% hint warning %}}
ElementX can not yet access spaces. Use a different client, or [SchildiChat Next](https://schildi.chat/android/next/) which is a fork of ElementX with spaces support.
{{% /hint %}}

1. Open the "Join Rooms" screen (+ -> "Rooms" in Element)
2. Join the room with your state
3. Tap your state's space menu in the sidebar, and click "Explore Rooms"
4. Join the channel for your metropolitan area
{{% /tab %}}
{{% /tabs %}}

## I've successfully joined, how come I can't see anything?

This is a side effect of E2EE (end-to-end encryption). For security and privacy purposes, the server doesn't store the messages directly. Instead, clients send their messages in an encrypted form, and the decryption keys go directly from their client to yours. This system is very secure, but it breaks the ability to go back and read old messages. Next time someone sends a message, you should be able to see it!