





PHP: mail() function sending email
	
		mail(to, subject, message, heders, parameters)

		to        : required and sepecifies the receiver/receivers of the email
		subject   : required and  specifies the subject of the mail. 
					 This parameter cannot contain any newline charecters.
		message   : required and Defines the message to be sent. each line should be 	             separated with a LF -> Lines should not exceed 70 characters.
		headers   : Optional. speicifies additional headers, like From, Cc, and Bcc. The
					 additional headers should be separated with a CRLF(\r\n)
		parameter : Optional. Specifies an additional parameter to the sendmail program.