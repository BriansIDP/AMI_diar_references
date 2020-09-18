<h2> AMI MDM Diarisation Partition </h2>

Train set meetings: AMI.SA.meetings.txt
Train set speakers: AMI.SA.speakers.txt
Dev set meetings: AMI.SB.meetings.txt
Dev set speakers: AMI.SB.speakers.txt
Eval set meetings: AMI.SC.meetings.txt
Eval set speakers: AMI.SC.speakers.txt

Note: Train set differs from the [full corpus ASR partition](http://groups.inf.ed.ac.uk/ami/corpus/datasets.shtml) in the following 2 ways:
1. Train set includes meeting IB4005, which is consistent with the [ASR partition in Kaldi recipe](https://github.com/kaldi-asr/kaldi/blob/master/egs/ami/s5/local/split_train.orig)
2. Train set excludes meeting IS1003b and IS1007d since they only have one single-distance microphone data. 

<h2> AMI MDM reference files </h2>

e.g. dev set reference:

original references:
dev_orig/AMIMDM-<Meeting_ID>.rttm

modified references:
dev/AMIMDM-<Meeting_ID>.rttm
