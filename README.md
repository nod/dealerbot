# dealerbot

## a holden tournament irc bot

This is an updated fork of Paul Rotering's pytbot.  Minimal work was done to
make this run today.  He deserves all the credit.

## getting started

- create a virtualenv, because REASONS
- pip install -r requirements.all
- ./pytbot
- PROFIT!



# Old README follows:





    Copyright (C) 2004-2007 Paul Rotering

    This program is free software; you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation; either version 2 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program; if not, write to the Free Software
    Foundation, Inc., 59 Temple Place - Suite 330, Boston, MA 02111-1307, USA

Please send any questions or comments to [redacted so he doesn't get spammed]

Modify pytbot.ini to point to the  IRC server you want to use.

All dealer commands are of the form 'p cmd [arg1 [arg2]]'.  'p help'
gives a list of most commands.  ***Please note that many IRC servers
using flood protection will kick pytbot if users ask for help (or even
if the game is moving quickly!).  It works best if you can get an
admin of the server to turn off flood protection for the bot.***
