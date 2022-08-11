# Welcome to White-prince :crown:

[![White-prince](https://github.com/White-prince/White-prince/blob/main/assets/White-prince_01.jpg?raw=true)](https://white-prince.github.io/Homepage/)

You can follow me on my social networks:

[![Twitter](https://img.shields.io/badge/-Twitter-131313?style=for-the-badge&logo=Twitter)](https://twitter.com/White_prince_0)

[![Instagram](https://img.shields.io/badge/-Instagram-131313?style=for-the-badge&logo=Instagram)](https://www.instagram.com/0xe_white_prince_ex0/)

[![Telegram](https://img.shields.io/badge/-Telegram-131313?style=for-the-badge&logo=Telegram)](https://t.me/Dark_Hub_info)

[![VK](https://img.shields.io/badge/-VK-131313?style=for-the-badge&logo=VK)](https://vk.com/id333667069)

[![Facebook](https://img.shields.io/badge/-Facebook-131313?style=for-the-badge&logo=Facebook)](https://www.facebook.com/profile.php?id=100023988285502)

# White-prince Vkontakte_bot :robot:
The bot facilitates the work of Vedmenko production employees.

## Installation :gear:
If you are cloning a project, run it first, otherwise you can download the source on the release page and skip this step.

    git clone https://github.com/White-prince/Vedmenko_vk_bot.git
    
You will need to install the libraries before starting the assistant

    pip install vk_api
    
You will also need a token to run your bot

## Usege :information_source:
The token can be obtained in the community settings, you can also log in through your profile. Insert the token into the config file.

    TOKEN = ''
To send notifications to admins, use their id

    admin_id = ''

Write the command in the terminal:

    python vk_bot.py

About the code:
- The file config.py contains login information

To send messages we use:

        def send_some_msg(id_user, message, keyboard=None):
        post = {'user_id': id_user, 'message': message, 'random_id': 0}
        if keyboard is not None:
            post['keyboard'] = keyboard.get_keyboard()
        else:
            pass
        session.method("messages.send", post)

Code base :
    
        if __name__ == '__main__':
 
All other features are pretty standard.

Hope this code helps you :crown:
