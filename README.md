Social Media Share Buttons
========

Wiki macros implementation of some common social media share buttons.

Usage
=====

    {{shareon media='all' twitterText='Check out' hashtags='awesome' pinterestMedia="$!{myImage}" mailContent="I thought you might be interested in:"/}}

Social network that can be used
-------------------------------

|Email     | email 
|Facebook  | facebook
|Google+   | googleplus
|LinkedIn  | linkedin
|Pinteres  | pinterest
|Twitter   | twitter
|Print     | print

Parameters you can use
----------------------
 
'media' - you can specify which social network you want to share on ex: media="facebook, googleplus", 'all' being the default.
'twitterText' - text that will be inserted automatically in the body of the tweet preceding the url you are sharing (can be edited at the moment of sharing)
'hashtags' - the hashtags that will be inserted automatically in the body of the tweet after the url you are sharing (can be edited at the moment of sharing)
'pinterestMedia' - url of the image you want to be used when sharing with pinterest
'mailContent' - text in the body of the email that will be inserted automatically preceding the url you are sharing
