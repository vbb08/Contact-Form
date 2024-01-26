# Contact-Form

HTML contact form via PHPMailer, using Gmail account.


## Requirements:
- PHPMailer
- Gmail account credentials

## Setup Instructions
- Check on GitHub repo https://github.com/PHPMailer/PHPMailer to download and install PHPMailer
- In mail.php file configure PHPMailer, indicating your email address and SMTP password, provided by Gmail account

```
    $mail->isSMTP();                              //Send using SMTP
    $mail->Host       = 'smtp.gmail.com';       //Set the SMTP server to send through
    $mail->SMTPAuth   = true;             //Enable SMTP authentication
    $mail->Username   = '###############@gmail.com';   //SMTP write your email
    $mail->Password   = '#################';      //SMTP password
    $mail->SMTPSecure = 'ssl';            //Enable implicit SSL encryption
    $mail->Port       = 465;   
```


```
    $mail->addAddress('##############@gmail.com');     //Add a recipient email
```



- Run contact form.html and visit your local host

## My personal working contact form can be checked [here](https://testingwebsite.free.nf/#contact)
<img width="672" alt="contactform" src="https://github.com/vbb08/Contact_form/assets/67701977/a065f1b8-f1ee-40a9-8ebf-835aa0016517">
