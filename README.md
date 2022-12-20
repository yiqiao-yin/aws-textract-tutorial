# AWS Tutorial

<p align='center'>
    <img src="https://raw.githubusercontent.com/yiqiao-yin/aws-textract-tutorial/main/diagram/textract-diagram.png" width=600 height=430></img>
</p>

## Background: OCR

**Optical character recognition (OCR)** plays an important role in transforming printed materials into digital text files. These digital files can be very helpful to kids and adults who have trouble reading. That’s because digital text can be used with software programs that support reading in a variety of ways.

OCR was first introduced in the 1990s. Fast-forward to today, and you’ll find OCR built into the software of many programs and devices, including some computers, tablets, phones and printers. Many of these devices can automatically convert a scanned or photographed document into digital text.

Digital text is one of several formats that make printed information accessible to more people. (Other formats include audio, large print and Braille.) Digital text is especially helpful for struggling readers, including those who have learning differences such as dyslexia. The digital format makes it possible for readers to see words on a screen and hear them read aloud at the same time. This provides more ways to engage with the information. It can also help kids develop independent reading skills.

## What is AWS Textract

Amazon Textract is a machine learning (ML) service that automatically extracts text, handwriting, and data from scanned documents. It goes beyond simple optical character recognition (OCR) to identify, understand, and extract data from forms and tables. Today, many companies manually extract data from scanned documents such as PDFs, images, tables, and forms, or through simple OCR software that requires manual configuration (which often must be updated when the form changes). To overcome these manual and expensive processes, Textract uses ML to read and process any type of document, accurately extracting text, handwriting, tables, and other data with no manual effort. You can quickly automate document processing and act on the information extracted, whether you’re automating loans processing or extracting information from invoices and receipts. Textract can extract the data in minutes instead of hours or days. Additionally, you can add human reviews with Amazon Augmented AI to provide oversight of your models and check sensitive data.

So, what are some important use cases?

## Financial services

    Accurately extract critical business data such as mortgage rates, applicant names, and invoice totals across a variety of financial forms to process loan and mortgage applications in minutes.

## Healthcare and life sciences

    Better serve your patients and insurers by extracting important patient data from health intake forms, insurance claims, and pre-authorization forms. Keep data organized and in its original context, and eliminate manual review of output.

## Public sector

    Easily extract relevant data from government-related forms such as small business loans, federal tax forms, and business applications with a high degree of accuracy.

You can read more about **AWS Textract** [here](https://aws.amazon.com/textract/)!

## What is in this repo?

This is an introductory github repo to save materials used to create the above pipeline which includes many building blocks of AWS services. The repo intends to build a fundamental understanding of how to put together a few AWS resources. The topic is to use `textract` function from **AWS** to allow users to upload `.pdf` files to trigger **Lambda functions**.

## Other References

<ul>
<li><a href="https://docs.aws.amazon.com/">AWS Docs</a></li>
<li><a href="https://github.com/srcecde/aws-lambda-cheatsheet">AWS Lambda Cheatsheet</a></li>
</ul>
