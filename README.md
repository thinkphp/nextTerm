nextTerm
========

This plugin MooTools finds the next number in the sequence of integers using [difference table](http://www.algebra.com/algebra/homework/Sequences-and-series/Sequences-and-series.faq.question.155130.html).

![Screenshot](http://farm3.static.flickr.com/2304/5747428033_259c271b02.jpg)

How to use
----------

First you must to include the JS files in the head of your HTML document.

        #HTML
        <script src="http://www.google.com/jsapi?key=ABQIAAAA1XbMiDxx_BTCY2_FkPh06RRaGTYH6UMl8mADNa0YKuWNNa8VNxQEerTAUcfkyrr6OwBovxn7TDAH5Q"></script>
        <script type="text/javascript">google.load("mootools", "1.3");</script>
        <script type="text/javascript" src="nextTerm.js"></script>


Problem: I need to know what number comes next in this sequence?

       #JS
       var sequence = [9,73,241,561,1081,1849];
       //solution:
       console.log("Next number comes next in this sequence is:" + sequence.nextTerm());
       console.log(sequence.combine([sequence.nextTerm()]));
       