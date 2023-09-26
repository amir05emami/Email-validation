# Email-validation
email = input('enter your email: \n')
x = email.find('@')
after = email [x+1:]

if '@' in email:
    if after == 'gmail.com':
        print('true')
    elif after == 'yahoo.com' :
        print('true')
    else:
        print('false')
else:
    print('false')
