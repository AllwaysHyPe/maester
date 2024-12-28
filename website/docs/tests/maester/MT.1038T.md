---
title: MT.1038 - Only invited users should be automatically admitted to Teams meetings
description: TBD (Teams)
slug: /tests/MT.1038
sidebar_class_name: hidden
---

# Only invited users should be automatically admitted to Teams meetings

## Description

> Users who aren’t invited to a meeting shouldn’t be let in automatically, because it increases the risk of data leaks, inappropriate content being shared, or malicious actors joining. If only invited users are automatically admitted, then users who weren’t invited will be sent to a meeting lobby. The host can then decide whether or not to let them in.

## How to fix

> 1. Log into Microsoft Teams admin center
> 2. In the left navigation, go to Meetings > Meeting Policies
> 3. Under Manage Policies, select a group/direct policy
> 4. Under the Meeting join and lobby section, toggle "Who can bypass the lobby" to "People who were invited"
> 5. You’ll need to change this setting for each group/direct policy
