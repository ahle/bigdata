### send the email 
airflow.cfg
```
[smtp]

# If you want airflow to send emails on retries, failure, and you want to use
# the airflow.utils.email.send_email_smtp function, you have to configure an
# smtp server here
smtp_host = smtp.gmail.com
smtp_starttls = False
smtp_ssl = True
# Example: smtp_user = airflow
smtp_user = ***@gmail.com
# Example: smtp_password = airflow
smtp_password = *******
smtp_port = 465
smtp_mail_from = ***@gmail.com
```
