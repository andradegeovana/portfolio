+++
widget = "contact_form"
title = "Contato" 

# Uncomment the following line and widget will NOT be displayed
# hidden = true

# Uncomments the following line for
# standard forms.
#
# Form handler
# action = "/contact_handler.php"
# Form submit method
# method = "GET" # Default is POST

# For Netlify form
#
netlify = true

# Add a contact via email button if your email
# is configured in the config file of your website.
useEmail = true

# Form inputs
[[inputs]]
label = "Seu nome"
# Input type
type = "text"
# minimum input length
minlength = "3"
# maxlength = "25"
name = "name"
# pattern matching
pattern = "[a-zA-Z]+"
placeholder = "Nome"
# The input is required to submit the form
# required = true

[[inputs]]
label = "Seu e-mail"
type = "email"
name = "email"
# pattern = ""
placeholder = "Email"
required = true

# Textarea works same as input but doesn't support pattern matching
[[inputs]]
label = "Sua mensagem (mínimo 10 caracteres)"
type = "textarea"
# pattern is not supported on textarea
name = "message"
placeholder = "Sua mensagem..."
required = true

+++

Deseja entrar em contato comigo? 
