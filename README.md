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

### Below, contact form and email received examples displayed:
<img width="670" alt="contact form" src="https://github.com/vbb08/Contact-Form/assets/67701977/c1cacd04-f6f2-40df-9dfa-f1a0fa98fb65">

<img width="615" alt="email" src="https://github.com/vbb08/Contact-Form/assets/67701977/865eaa0f-3360-4439-8ec3-7f51d0ce8371">
