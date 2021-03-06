# Onboarding Cloud9 with AWS Educate

*Last Update:* August 21, 2020

These notes were written originally by @sirocknick
in June 2020, and have been revised by @michaelsoltys . The notes are
meant for students who are being introduced to the Cloud9 IDE
(Integrated Development Environment) with AWS Educate.

# Introduction

These notes will guide you in setting up a **development
environment** - the place where you go to write and run code - using
an AWS Educate account and Cloud9. In order to get a bird eye of view
of what Cloud9 is, please watch this video: https://youtu.be/JDHZOGMMkj8

## Advantages of Cloud9:

* Anyone with access to the Internet can access it at any time without
needing to install anything. This is extremely important as students
might have different types of computers.

* It is free (at least to the degree that we are using it).

* It has a built in UNIX based terminal, which is convenient.

* It has a variety of features built in for collaboration, sharing,
and chat support.

It is important to note that when using Cloud9, you are not actually
running it on your own computer. You are connected to a
different computer over the Internet. Any changes you make will not
affect your computer and instead will stay on the computer Cloud9 is
running on. Each time you log in to Cloud9 you connect automatically
to the same computer, even if you are connecting from a different
computer or laptop on your end.

The first step consists in opening an AWS Educate account, and it
involves a validation process that can take up to a day or two, and so
it is important that you start this process as soon as possible.

# Step 1 Activate Your Account Through The Email Sent To You

You should receive an email invitation to access the AWS resources.
This email will have the subject line:

```
Your AWS Educate Application
```

The email will look something like this:

![](./SetUpCloud9/SetUp1.png)

If you do not see this email, first check appropriate Spam folders,
and then contact your instructor so that it can be resent.

You are going to want to click the "here" link inside of the email and
fill out the application. The application will look something like
this:

![](./SetUpCloud9/SetUp2.png)

Do not worry about the promo code section, and set your graduation
date to something reasonable (but make sure it is a date in the
future!). Enter the other information and click "Next".

Sometimes you will get another screen, or it might take you right to
the email verification step. If you have another screen, on the choose
one of the following page, select "Click here to select an AWS Educate
Starter Account", and then choose "Next".

You then should recieve an email from AWS meant to confirm that you
actually own the provided email address.  Verify your email address by
clicking the link in that email.

After clicking next, it should tell you that your application was
received and that you will be emailed when it is processed. This
processing is said to usually take 1 day.

After AWS Educate approves your application, AWS will send you an
email with the title "AWS Educate Application Approved". 

You will not be able to progress further in setting up your
development environment until this application has been processed. 

# Step 2: Sign Into Your AWS Educate Account

When you get the approval email, follow the instructions in it to set
your AWS Educate Student Portal password, and then sign in to your AWS
Educate Student Portal. 

![](./SetUpCloud9/SetUp3.png)

After you set your AWS Educate Student Portal password, store that
password in a secure location. You will be using these credentials all
semester, although you can recover your password if you forget it.

Use this link to login:

https://www.awseducate.com/signin/SiteLogin

# Step 3: Go Into The AWS Classroom

Once setting your password, you should be on the following screen. You
are going to want to go to "My Classrooms". It is one of the large
colorful buttons near the bottom of the screen.

![](./SetUpCloud9/SetUp4.png)

It is possible for you to have multiple classes using AWS.  On the row
with "Introduction to Programming" click the big blue "Go to
Classroom" button.

![](./SetUpCloud9/SetUp5.png)

At this point a pop up message will display regarding the Terms and
Conditions for the website. Read these to the degree that you wish.
Then click "Continue" to proceed.

![](./SetUpCloud9/SetUp6.png)

You are then going to be redirected to a page containing more
conditions. Again, read these to the degree that you wish. Eventually
you will reach the bottom of these, and be able to click "I agree"

![](./SetUpCloud9/SetUp7.png)

# Step 4: Go to the AWS Console

You will now be on a page with a lot of different things going on that
looks kind of confusing. On the right half of the screen there will be
two blue buttons. You want to click the button "AWS Console".

![](./SetUpCloud9/SetUp8.png)

At this point you will be presented with the AWS Management Console.
While we are using it for a very specific purpose in this class, this
is a tool that millions of developers use to do Cloud Computing. I
have used it every day in my work for the past 2 years.

![](./SetUpCloud9/SetUp9.png)

You will notice that near the middle of the screen there is a search
box.

Inside of the search box, type Cloud9 and click on it when it appears
in the results.

![](./SetUpCloud9/SetUp10.png)

# Step 5: Setting Up Cloud9

You should now be on a screen introducing Cloud9. On the right side of
the screen there is an orange button that says "Create Environment",
this is where you need to go next.

![](./SetUpCloud9/SetUp11.png)

You should now see a form asking for a name and description for the
environment. Give the environment a name like "My Coding Environment".
Don't worry about the description. Then click "Next Step"

![](./SetUpCloud9/SetUp12.png)

You will now be on a screen with what looks like a lot of scary
options that you don't understand. These are different computer
options. Don't worry about them. For this class, you will only need
the most basic computer. So, you are going to ignore all of these
options. Instead, just scroll to the bottom.

![](./SetUpCloud9/SetUp13.png)

![](./SetUpCloud9/SetUp14.png)

You will next be on a review screen, scroll to the bottom and click
"Create Environment"

![](./SetUpCloud9/SetUp15.png)

You should be now on a loading screen that says it is creating your
Cloud9 environment. Congratulations, you have basically finished.

![](./SetUpCloud9/SetUp16.png)

You should now be on a welcome screen. Near the top, there is a bar
that says Welcome, you can click x to close this welcome screen.

![](./SetUpCloud9/SetUp17.png)


You should now see a mostly black screen. Don't worry, this is where
you want to be.

![](./SetUpCloud9/SetUp18.png)

# Hello, World

We will now write the first program in C, Java and Python. It is
customary that a new programming language be celebrated by writing a
"Hello, World" program. We do so in each of the three languages.

## C

[Hello World in C](./HelloWorld-c.md)

## Java

[Hello World in Java](./HelloWorld-java.md)

## Python

http://greenteapress.com/thinkpython2/html/thinkpython2002.html#sec8
