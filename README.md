# Lead Attribution Data Quality Assessment

## Business Question

**Which lead channels are producing the strongest sales outcomes?**

The original goal was to compare channels such as Phone, Website, Thumbtack, Angi, Valpak, and referrals to see which were producing the best results.

## What I Found

Before building the analysis, I reviewed how lead sources were actually being tracked in Housecall Pro.

The biggest issue was that lead source was mostly being added at the **job stage**, not consistently when the lead or estimate was created.

In the estimate report:

* 292 estimates were reviewed
* 276 had no lead source assigned
* Only 16 had a source assigned

That means about **94.5% of estimates were missing lead-source attribution**.

The job report had much better source tagging, but by that point I was only looking at jobs that had already been sold.

## Why the Original Analysis Would Be Misleading

To compare conversion rates fairly, each channel needs the same starting point.

For example:

Lead → Estimate → Sale

Thumbtack and Angi keep records of their original leads, but Housecall Pro did not consistently track the original Phone, Website, Valpak, and other leads.

Because of that, I could see how many tagged jobs were sold, but I could not reliably determine how many original opportunities each channel started with.

A conversion ranking would therefore compare different populations and could give the business the wrong answer.

## Decision

I stopped the performance analysis instead of creating a dashboard from data that could not support the original question.

The historical data can still show things such as recorded job volume and revenue by source, but it cannot reliably show which channel has the best lead-to-sale or estimate-to-sale conversion rate.

## What Needs to Change

Lead source should be captured when the customer first enters the business and kept through the rest of the sales process.

The future process should look like:

Lead + Source → Estimate → Won/Lost → Job + Revenue

This would make it possible to accurately compare:

* Lead-to-sale conversion
* Estimate win rate
* Revenue per lead
* Revenue by channel
* Average job value

The next step for this project is designing the updated lead-tracking workflow so future channel performance can be measured correctly.


The Process Improvement I Created

After identifying the attribution gap, I created a simple workflow showing when lead source information should be collected and how it should carry through the sales process.

I also created a short SOP for the employee responsible for lead intake so new leads are recorded consistently going forward.

The updated process is designed to make future channel performance analysis possible using a consistent starting point:

Lead + Source → Estimate → Won/Lost → Job + Revenue
