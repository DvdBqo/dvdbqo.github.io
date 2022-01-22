# dvdbqo.github.io
baseURL = "http://https://dvdbqo.github.io/"
# [en, zh-cn, fr, ...] determines default content language
defaultContentLanguage = "es"
# language code
languageCode = "es"
title = "DvdBqo"

# Change the default theme to be use when building the site with Hugo
theme = ""

[params]
  # LoveIt theme version
  version = "0.2.X"

  [params.header.title]
     name = "DvdBqo"
      
     pre = "<i class='fas fa-crow fa-fw'></i>"

  [params.home.profile]
     enable = true
     # Gravatar Email for preferred avatar in home page
     gravatarEmail = ""
     # URL of avatar shown in home page
     avatarURL = "/yo2.png"
     # title shown in home page (HTML format is supported)
     title = "D4V1D B4Q¬3rO"
     # subtitle shown in home page
     subtitle = "Automation & Industrial Electronic Engineer"
     # whether to use typeit animation for subtitle
     typeit = true
     # whether to show social links
     social = true
     # disclaimer (HTML format is supported)
     disclaimer = ""
#[params.social]
  #[params.social.LinkedIn]
    # weight when arranging icons (the greater the weight, the later the icon is positioned)
#    weight = 0
    # your social ID
 #   id = "in/david-baquerod"
    # prefix of your social link
  #  prefix = "https://linkedin.com/"
    # content hovering on the icon
   # title = "LinkedIn"
  [params.social.Github]
    # weight when arranging icons (the greater the weight, the later the icon is positioned)
    #weight = 1
    # your social ID
    #id = "@DvdBqo"
    # prefix of your social link
    #prefix = "https://github.com/"
    # content hovering on the icon
    #title = "Github"
   [params.home.posts]
      enable = true
      paginate = 3

[menu]
  [[menu.main]]
    identifier = "posts"
    # you can add extra information before the name (HTML format is supported), such as icons
    pre = "<i class= 'fas fa-pen-nib fa-fw' ></i>"
    # you can add extra information after the name (HTML format is supported), such as icons
    post = ""
    name = "Posts"
    url = "/posts/"
    # title will be shown when you hover on this menu link
    title = ""
    weight = 1
  [[menu.main]]
    identifier = "tags"
    pre = "<i class='fas fa-flag fa-fw'></i>"
    post = ""
    name = "Tags"
    url = "/tags/"
    title = ""
    weight = 2
  [[menu.main]]
    identifier = "categories"
    pre = "<i class='fas fa-archive fa-fw'></i>"
    post = ""
    name = "Categories"
    url = "/categories/"
    title = ""
    weight = 3
  [[menu.main]]
    identifier = "about"
    pre = "<i class='fas fa-user-tie fa-fw'></i>"
    post = ""
    name = "About"
    url = "/about/"
    title = ""
    weight = 5

# Markup related configuration in Hugo
[markup]
  # Syntax Highlighting (https://gohugo.io/content-management/syntax-highlighting)
  [markup.highlight]
    # false is a necessary configuration (https://github.com/dillonzq/LoveIt/issues/158)
    noClasses = false
