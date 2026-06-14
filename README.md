# Lead-to-Revenue-Pipeline-Dashboard
<p>
  A pipeline analytics project built on B2B CRM data, loaded into Salesforce, modeled in Power BI, and turned into a dashboard that answers the question most sales 
  teams can't: where are we leaking revenue, and why?
</p>

<p>
  Built with Salesforce, Power BI, DAX, and SQL. <br>
  Data: Maven Analytics CRM Sales Opportunities (~8,800 opportunities)
</p>

## The Problem
<p>
  Most teams can tell you how much they sold. Far fewer can point to where deals fall out of the pipeline, which segments actually convert, or how long a 
  winning deal takes to close. A raw CRM export doesn't answer any of that. The data has to be structured, related, and measured first.
</p>
 This project takes a sales dataset from a fictional hardware company and turns it into a decision-support dashboard covering four things a sales leader 
  actually cares about:
<ul>
  <li><b>Pipeline health:</b> what's open, what it's worth, and how deals are distributed across stages</li>
  <li><b>Conversion and leakage:</b> win rate, where deals drop off, and which reps/segments underperform</li>
  <li><b>Revenue by segment:</b> which products, sectors, regions, and account sizes drive revenue</li>
  <li><b>Deal-level detail:</b> drill-through from any number down to the individual opportunities behind it</li>
</ul>

## What's in the dashboard
<ul>
  <li>Pipeline Health: Open pipeline value, weighted forecast, win rate, average deal size, sales cycle, and revenue trend</li>
  <li>Conversion & Leakage: Win rate by region/sector/product, won-vs-lost cycle time, and an agent volume-vs-win-rate view</li>
  <li>Revenue & Segments: Revenue by product, sector, region, and company size band</li>
  <li>Deal Detail: Drill-through table showing every opportunity behind a selected rep or product</li>
</ul>
<br>
## A few things the data showed
<ul>
  <li>Lost deals closed faster than won ones across every product line. The takeaway: a deal still alive past the average time-to-loss isn't stalling, it's 
      maturing, and it's more likely to win. Giving up on slow-moving deals is often the wrong call.</li>
  <li>~63% overall win rate, but the average hid real gaps once split by segment.</li>
  <li>Large and Enterprise accounts drove the majority of revenue.</li>
  <li>The highest-volume reps weren't the highest-converting ones, a sign that activity doesn't equal outcome.</li>
</ul>

![Lead-to-Revenue-Pipeline-Dashboard](https://github.com/Divya295-hub/Lead-to-Revenue-Pipeline-Dashboard/blob/main/Pipeline%20Health%20Overview.png)

## Conclusion
<p>
  What started as a flat CRM export ended as a dashboard a sales team could actually make decisions from — but the value wasn't in the charts. It was in the 
  choices underneath them: keeping open-deal blanks instead of deleting them, mapping names to IDs so the data would load cleanly, and measuring conversion in a 
  way the data could honestly support. Those decisions are what separate a report that looks finished from one that holds up when someone asks, "Where did this 
  number come from?"
  The most useful lesson was that the hardest part of analytics usually isn't the visualization, it's understanding the data well enough to know what's real, 
  what's missing, and what's simply not there yet. The "lost deals close faster" finding only surfaced because the model was built to ask the right question, 
  not just plot the obvious one.
</p>
