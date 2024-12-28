---
title: MT.1040 - Restrict anonymous users from starting Teams meetings
description: TBD (Teams)
slug: /tests/MT.1040
sidebar_class_name: hidden
---

# Restrict anonymous users from starting Teams meetings

## Description

> If anonymous users are allowed to start meetings, they can admit any users from the lobbies, authenticated or otherwise. Anonymous users haven’t been authenticated, which can increase the risk of data leakage.

## How to fix

> 1. Log into Microsoft Teams admin center
> 2. In the left navigation, go to Meetings > Meeting Policies
> 3. Under Manage Policies, select a group/direct policy
> 4. Under the Participants & guests section, toggle "Let anonymous people start a meeting" to Off
> 5. You’ll need to change this setting for each group/direct policy
