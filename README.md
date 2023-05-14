# Welcome to Regidf
# Vkontakte_bot :robot:
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

## About the code :electron:
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

Hope this code helps you
