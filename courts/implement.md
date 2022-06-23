# Notes on implementation of jury trials in India

# 1

**How many more judges will we need to conduct 200,000 trials concurrently?**

I think we can conduct 200,000 jury trials concurrently with our present 20,000 judges. We don't need to recruit a single new judge for conducting 200,000 jury trials at a time. 

In order to prove this to you, I first need to prove that judges and juries can function asynchronously.

Basically, the judge will **not** sit beside the jury while the trial is being conducted. 1 judge will be responsible for answering questions of law for 10 jury trials. The judge can answer questions of law without the jury being present except deciding whether an objection to [questions to / answers of] witnessds or arguments of either counsel. The procedure for deciding on the admissibility of evidence and whether an objection should be sustained or overruled can be as follows:

1. The plaintiff's and defendant's counsel will document (a) all evidence and (b) all the questions they wish to ask any witness before the trial starts to the judge. 
2. The judge will give evidence and the list of questions to the opposing counsel once he received them. The opposing counsel can then send a list of all objections they have against certain evidence or questions. 
3. The judge will then decide whether an evidence is admissible or not a particular evidence is admissible or whether he wants to sustain or overrule an objection. The judge will document all admissible evidence and the lists of all questions to which there were no objections or they were overruled and provide that document to both counsels and the "case coordinator" (let's call this "the case file" for now).
4. If any counsel presents in front of the jury an evidence deemed in admissible by the judge or a question to which the objection has been sustained, the opposing counsel can raise an objection. 
5. The case coordinator will then verify from the case file and tell the jury whether the arguing is counsel presenting an inadmissible evidence or a question against which the objection was sustained. If either counsel disagrees with the case coordinator, they can show their case files to the jury. The jury's decision on whether they want to see the evidence or hear the witness' answer to the question will be final.

This way judges and juries can function asynchronously.

Now, I need to prove whether it is possible for 1 judges to answer questions of law for 10 trials at a time. [[1](https://www.indiabudget.gov.in/budget2019-20/economicsurvey/doc/vol1chapter/echap05_vol1.pdf)] shows that Indian district & sessions court judges dispenses judgement on 746 cases a year. If they work for 250 days (which they don't if you consider summer and winter vacations), they'll be disposing 3 cases per day. So, it is pretty reasonable to expect them to answer the questions of law which can be answered before proceeding starts (including addressing objections during witness testimony or closing arguments) for 10 cases within a weekend before the trial starts. Then they'll have (6 hours / 10 cases = roughly 30 minutes per case) to answer questions of law which need to be answered during the trial (including addressing objections during witness testimony or closing arguments).
