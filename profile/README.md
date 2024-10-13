<br>

> [!NOTE]
> Contiunuously Updated

<br>

### Expectations

Outcome
> * A reduction in the time, and hence cost, of detecting, classifying, and masking sensitive text.
> * Minimal error rate, hence a near zero error cost, i.e., near zero error liabilities.

<br>

Objective
> A **false negative rate cost** per **text class** is $<£250,000$ during the first $3$ years.
>
> whereby
> 
> **false negative rate cost** = *fnr* $\times N\_{\_{c}} \times weight_{_{c}}$

Herein, *fnr* is the requisite false negative rate [maximum] limit, $N\_{\_{c}}$ will be the maximum number of errors viv-&agrave;-vis the text class, and $weight_{_{c}}$ is the cost of a text class. The text class is organisation dependent because each will have its own taxonomy.  For example, it might decide to mask text that fall into the groups

* organisation
* full name
* address: residential & commercial
* chemical name
* chemical processes
* internet protocol
* telephone numbers
* banking details: all types
* financial details: all types

During the first three years, an organisation might decide that the weight of publishing, e.g., a client's bank details is $£85,750$, and that of a name is $£27,100$.  Hence, the number of bearable errors per class differs during the three year period, and the model must be evaluated/tested against the expected business expectations.

<br>
<br>

### Set Up

* An Amazon ECR (Elastic Container Registry) Repository

<br>
<br>

<br>
<br>

<br>
<br>

<br>
<br>

<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
