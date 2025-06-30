###########################################################
### Beautiful Jekyll _config.yml for Mina’s Math Portfolio
###########################################################

############################
# --- Required options --- #
############################

# Name of website
title: "Mina Basilious Hanna Arsanious"

# Your name to show in the footer
author: "Mina Basilious Hanna Arsanious"

###############################################
# --- List of links in the navigation bar --- #
###############################################

navbar-links:
  Home: "/"
  LinkedIn: "https://www.linkedin.com/in/mina-basilious/"
  "Math Art Gallery": "https://minabasilious.github.io/Minas-Math-Art-Gallery/"

################
# --- Logo --- #
################

# optional avatar; remove or update path if unused
avatar: "/assets/img/avatar-icon.png"
round-avatar: true

#####################################
# --- Footer social media links --- #
#####################################

social-network-links:
  email: "basiliousmina2@gmail.com"
  github: "minabasilious"
  linkedin: "mina-basilious"
  youtube: "@minabasil"

rss-description: "Current pure mathematics work and projects"

###########################
# --- General options --- #
###########################

# Excerpt settings (not used heavily here)
excerpt_length: 25
feed_show_excerpt: false
feed_show_tags: false

# Search and edit links
post_search: false
edit_page_button: false

# Show title on all pages
title-on-all-pages: true

######################################
# --- Colours / background image --- #
######################################

page-col: "#FFFFFF"
text-col: "#333333"
link-col: "#0066CC"
hover-col: "#0055AA"
navbar-col: "#F8F8F8"
navbar-text-col: "#333333"
footer-col: "#F8F8F8"
footer-text-col: "#555555"
footer-link-col: "#0066CC"
footer-hover-col: "#0055AA"

####################
# --- Comments --- #
####################

# no comments/disqus for this minimal portfolio
#disqus: ""

################
# --- Misc --- #
################

timezone: "Africa/Cairo"
date_format: "%B %-d, %Y"

########################
# --- Defaults --- #
########################

defaults:
  -
    scope:
      path: ""
      type: "pages"
    values:
      layout: "default"

########################
# --- Plugins --- #
########################

plugins:
  - jekyll-paginate
  - jekyll-sitemap
