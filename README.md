# i-Ching-Texts-XML
Got a translation of the I Ching in xml format? Let's aggregate them!

The Wilhelm Baynes example here is not my work. I found it at [Ivan Zderadika's git here](https://github.com/izderadicka/iching/blob/master/text/en/hexagrams.xml) but it looks like an relatively robust XML format that we might use as a base for other translations and the starting sketch for a standard. 

I would propose:
a) We convene a standards group to figure out a universal Taxonomy for I Ching data structures. Who's in?
b) We upload here any structured translations we can find
c) Once a standard is agree, we start coding translators to take whatever structured data we can find, be it python or csv or what have you, and turn it into I Ching Standard Structured XML (ICSSXML)
d) Until a standard is agreed, start using this one and explore and document its limitations

The format:
```<hexagrams>
  <hexagram no="[1..64]">
    <name></name>
    <translated></translated>
    <comment></comment>
      <judgement>
        <predication></predication>
        <comment></comment>
      </judgement>
      <image>
        <predication></predication>
        <comment></comment>
       </image>
       <lines>
        <line no="[1..6]">
          <change></change>
          <predication></predication>
          <comment></comment>
         </line>
  </hexagram>
  </hexagrams>  
 ```




Example: 

```<hexagrams>
<hexagram no="1">
<name>Ch'ien</name>
<translated>The Creative</translated>
<comment>
The first hexagram is made up of six unbroken lines. These unbroken
lines stand for the primal power, which is light-giving, active, strong,
and of the spirit. The hexagram is consistently strong in character, and
since it is without weakness, its essence is power or energy. Its image
is heaven. Its energy is represented as unrestricted by any fixed conditions
in space and is therefore conceived of as motion. Time is regarded as the
basis of this motion. Thus the hexagram includes also the power of time
and the power of persisting in time, that is, duration. The power represented
by the hexagram is to be interpreted in a dual sense in terms of its action
on the universe and of its action on the world of men. In relation to the
universe, the hexagram expresses the strong, creative action of the Deity.
In relation to the human world, it denotes the creative action of the holy
man or sage, of the ruler or leader of men, who through his power awakens
and develops their higher nature.
</comment>
<judgement>
<predication>
THE CREATIVE works sublime success, Furthering through perseverance.
</predication>
<comment>
According to the original meaning, the attributes [sublimity, potentiality
of success, power to further, perseverance] are paired. When an individual
draws this oracle, it means that success will come to him from the primal
depths of the universe and that everything depends upon his seeking his
happiness and that of others in one way only, that is, by perseverance
in what is right. The specific meanings of the four attributes became
the subject of speculation at an early date. The Chinese word here rendered
by "sublime" means literally "head," "origin," "great." This is why Confucius
says in explaining it: "Great indeed is the generating power of the Creative;
all beings owe their beginning to it. This power permeates all heaven."
For this attribute inheres in the other three as well. The beginning of
all things lies still in the beyond in the form of ideas that have yet to
become real. But the Creative furthermore has power to lend form to these
archetypes of ideas. This is indicated in the word success, and the process
is represented by an image from nature: "The clouds pass and the rain does
its work, and all individual beings flow into their forms." Applies to
the human world, these attributes show the great man the way to notable
success: "Because he sees with great clarity and cause and effects, he completes
the six steps at the right time and mounts toward heaven on them at the
right time, as though on six dragons." The six steps are the six different
positions given in the hexagram, which are represented later by the dragon
symbol. Here it is shown that the way to success lies in apprehending and
giving actuality to the way of the universe [Tao], which, as a law running
through end and beginning, brings about all phenomena in time. Thus each
step attained forthwith becomes a preparation for the next. Time is no longer
a hindrance but the means of making actual what is potential. The act of
creation having found expression in the two attributes sublimity and success,
the work of conservation is shown to be a continuous actualization and differentiation
of form. This is expressed in the two terms "furthering" (literally, "creating
that which accords with the nature of a given being") and "persevering"
(literally, "correct and firm"). "The course of the Creative alters and
shapes beings until each attains its true, specific nature, then it keeps
them in conformity with the Great Harmony. Thus does it show itself to further
through perseverance." In relation to the human sphere, this shows how the
great man brings peace and security to the world through his activity in
creating order: "He towers high above the multitude of beings, and all lands
are united in peace." Another line of speculation goes still further in
separating the words "sublime," "success," "furthering," "perseverance,"
and parallels them with the four cardinal virtues in humanity. To sublimity,
which, as the fundamental principle, embraces all the other attributes,
it links love. To the attribute success are linked the morals, which regulate
and organize expressions of love and thereby make them successful. The attribute
furthering is correlated with justice, which creates the conditions in which
each receives that which accords with his being, that which is due him and
which constitutes his happiness. The attribute perseverance is correlated
with wisdom, which discerns the immutable laws of all that happens and can
therefore bring about enduring conditions. These speculations, already broached
in the commentary called Wên Yen , later formed the bridge connecting
the philosophy of the "five stages (elements) of change," as laid down in
the Book of History (Shu Ching) with the philosophy of the Book of Changes,
which is based solely on the polarity of positive and negative principles.
In the course of time this combination of the two systems of thought opened
the way for an increasingly intricate number symbolism.
</comment>
</judgement>
<image>
<predication>
The movement of heaven is full of power.
Thus the superior man makes himself strong and
untiring.
</predication>
<comment>
Since there is only one heaven, the doubling of the trigram Ch'ien,
of which heaven is the image, indicates the movement of heaven. One complete
revolution of heaven makes a day, and the repetition of the trigram means
that each day is followed by another. This creates the idea of time.
Since it is the same heaven moving with untiring power, there is also
created the idea of duration both in and beyond time, a movement that
never stops nor slackens, just as one day follows another in an unending
course. This duration in time is the image of the power inherent in the
Creative. With this image as a model, the sage learns how best to develop
himself so that his influence may endure. He must make himself strong in
every way, by consciously casting out all that is inferior and degrading.
Thus he attains that tirelessness which depends upon consciously limiting
the fields of his activity.
</comment>
</image>
<lines>
<line no="1">
<change>Nine at the beginning means:</change>
<predication>
Hidden dragon. Do not act.
</predication>
<comment>
In China the dragon has a meaning altogether different from that given
it in the Western world. The dragon is a symbol of the electrically charged,
dynamic, arousing force that manifests itself in the thunderstorm. In
winter this energy withdraws into the earth; in the early summer it becomes
active again, appearing in the sky as thunder and lightning. As a result
the creative forces on earth begin to stir again. Here this creative
force is still hidden beneath the earth and therefore has no effect. In
terms of human affairs, this symbolizes a great man who is still unrecognized.
Nonetheless he remains true to himself. He does not allow himself to be
influenced by outward success or failure, but confident in his strength,
he bides his time. Hence it is wise for the man who consults the oracle
and draws this line to wait in the calm strength of patience. The time will
fulfill itself. One need not fear least strong will should not prevail;
the main thing is not to expend one's powers prematurely in an attempt to
obtain by force something for which the time is not yet ripe.
</comment>
</line>
</hexagram>

[...]

</hexagrams>```
