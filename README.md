# Apps.BadWords - Google Summer of Code 2021
<div  align="center">
	<img src="https://rocket.chat/wp-content/uploads/2021/02/Frame.png.webp" width="650" alt="google-summer-of-code">
	<br>
	<b>
		<p>
	Apps.BadWords : A Rocket.Chat App for bad words filtration for incoming messages and apply moderation policies.
		</p>
	</b>
</div>

# Abstract
Currently Rocket.Chat supports the bad words filtration of incoming messages in channels but that is not much customizable for the user. The idea for this App is to utilize the capabilities of Rocket.Chat.Apps-Engine and make a Rocket.Chat app which can provide a feature rich experience to the users and people can use the app according to their needs.

## Deliverables

The deliverables of the project are as follows:

- [x] Create a UI for managing the App settings.
- [x] Load a list of words from a URL.
- [x] Add/Remove words from a list.
- [x] Add/Remove channels where the bad words filtering is enabled (with a toggle for "all channels").
- [x] Provide statistics on blocked words and offending users.
- [x] Automatically deactivate users that go above a certain threshold.

All of the listed deliverables were completed within the GSoC period.

The App can be found here - [App on Github](https://github.com/RocketChat/Apps.BadWords).

### Links to Related Pull Requests

- Complete App - [https://github.com/RocketChat/Apps.BadWords/pull/1](https://github.com/RocketChat/Apps.BadWords/pull/1)

Apart from these contributions, I have contributed to other Rocket.Chat projects. They can be summarized as:
| Project                           | Reference                                                                                                                          |
| --------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------- |
| Rocket.Chat - main repo | [Pull requests](https://github.com/RocketChat/Rocket.Chat/pulls?q=is%3Apr+author%3Ayash-rajpal)                |
| Rocket.Chat.ReactNative | [Pull requests](https://github.com/RocketChat/Rocket.Chat.ReactNative/pulls?q=is%3Apr+author%3Ayash-rajpal+) |
| Opensource-Contribution-Leaderboard | [Pull requests](https://github.com/RocketChat/Opensource-Contribution-Leaderboard/pulls?q=is%3Apr+author%3Ayash-rajpal) |

## Features

The features of the project are as follows:

* Basic App Settings and Settings handler.
  * Settings Handler called every time any settings changes or when the app restarts.
 
* Getting the final list of blocked words. 
  * Fetching words from URL.
  * Getting user defined blocked words.
  * Removing user defined allowed words from the list of blocked words.
  * Getting list of Blocked words whenever app starts or restarts.
 
* Basic Message Filtering.
  * Checking the message against the list of blocked words at the time of saving new message and removing blocked words.
  * Cheking the message against the list of blocked words whenever any message is edited and removing the blocked words.

* Applying moderation policies for offending users
  * Storing the number of times a user uses bad words in a channel.
  * Banning a user and not letting the user send message in the room if the user exceeds the threshold limit set by admin.
  * Showing warnings to the users whenever a bad word in their message is found.

## Mentors

I would like to thank my mentors [Marcelo Schmidt](https://github.com/marceloschmidt) & [Douglas Gubert](https://github.com/d-gubert) for helping me complete the project and giving me this opportunity.


## 🔗 Links

<div  align="center">

| **Student**      |                                                    Yash Rajpal                                                    |
| :--------------- | :--------------------------------------------------------------------------------------------------------------------: |
| **Organization** |                           [Rocket.Chat](https://github.com/RocketChat)                           |
| **Project**      | [Apps.BadWords](https://github.com/RocketChat/Apps.BadWords) |
| **GitHub**       |                                       [yash-rajpal](https://github.com/yash-rajpal)                                        |
| **LinkedIn**     |                                [Yash Rajpal](https://www.linkedin.com/in/yash-rajpal-068998173/)                                |
| **Email**        |                    <a  href="mailto:rajpal.yash03@gmail.com">rajpal.yash03@gmail.com</a>                     |

</div>
