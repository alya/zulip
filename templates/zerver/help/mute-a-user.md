# Mute a user

!!! tip ""
    This feature mutes a user from your personal perspective, and does not
    alert administrators. Only organization [owners and
    administrators](http://localhost:9991/help/roles-and-permissions) can
    [deactivate users](/help/deactivate-or-reactivate-a-user).

You can mute any user you do not wish to interact with. Muting someone will
have the following effects:

- All messages sent by a muted user will automatically be [marked as
  read](/help/marking-messages-as-read) for you, and will never generate any
  desktop, push or email notifications.

- Muted users will be excluded from the list of users in the right sidebar, the
  [**Private messages**](/help/private-messages) list, and from the
  [mentions](/help/mention-a-user-or-group) autocomplete for you.

- In other places where you might encounter the muted user (e.g. [list of users
  who reacted with an emoji](/help/emoji-reactions#see-who-reacted-to-a-message)),
  their name will be replaced with **Muted user**. Note that all menus (e.g. list
  of stream subscribers) will continue to display the muted user's name.

!!! tip ""
    The user you muted will not know that they have been muted.


### Messages sent by muted users

Messages sent by muted users are hidden in your message feed:

- Stream messages and group private messages sent by muted users are hidden under a
  **Click to reveal** banner. The sender's profile picture, sender's name, and message content
  will be hidden until you reveal the message by clicking on it.

- Private messages between you and a user you have muted will not be visible
  unless you specifically [search](/help/search-for-messages) for them.

- If a muted user [mentions](/help/mention-a-user-or-group) you, the message will not be
  highlighted, but will still appear in the **Mentions** tab.


### From the message view

{start_tabs}

1. Click on a user's profile picture or [mention](/help/mention-a-user-or-group).

1. Click **Mute this user**.

1. On the confirmation popup, click **Confirm**.

{end_tabs}

### Via the right sidebar

{start_tabs}

1. Hover over a user's name in the right sidebar.

1. Click on the ellipsis (<i class="zulip-icon zulip-icon-ellipsis-v-solid"></i>) to
  the right of their name.

1. Click **Mute this user**.

1. On the confirmation popup, click **Confirm**.

{end_tabs}

### See your list of muted users

{start_tabs}

{settings_tab|muted-users}

{end_tabs}

From there, you can also search for and **unmute** users.

## Related articles

* [Mute a stream](/help/mute-a-stream)

* [Mute a topic](/help/mute-a-topic)
