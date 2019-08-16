---
layout: page
title: About
permalink: /about/
---

Hello and welcome to [swi.storyhouracademy.com](https://swi.storyhouracademy.com).

This is an open source project designed to collect word sums for all free and bound bases in Present-Day English.

# What is a base?

A base is a morpheme to which affixes, connecting vowel letters, or other bases may be added. A free base can stand alone as a word in English whereas a bound base can not. For example, \<do\> is a free base while \<pter\> is a bound base.

# What is a word sum?

A word sum is a hypothesis about the morphemic structure of a word. One way this type of hypothesis can be falsified is to apply suffixing conventions to the joins between each of the elements being added together. There are three suffixing conventions to check your joins with. These are:

1) With the **consonant doubling convention**, you must double the consonant letter of the morpheme on the left side of a join if the following conditions are met:

  * There is a suffix on the right side of the join that begins with a vowel letter.
  * There is a morpheme on the left side of the join that is either a single monosyllabic form or the stressed part of a polysyllabic form.
  * The morpheme on the left side of the join ends with a vowel letter grapheme followed by a consonant letter grapheme, but not \<w\> or \<x\>.  

  Examples:  
  cut + ing -> cutting  
  per + mit + ed -> permitted

  Note that a consonant at the end of a prefix will never double. Only a consonant at the end of a base or at the end of a suffix may double.

2) With the **final e convention**, you must replace the final \<e\> in the morpheme on the left side of a join if the following conditions are met:

  * The final \<e\> is an orthographic marker and does not represent a phoneme.
  * The suffix on the right side of the join begins with a vowel letter.  

  Examples:  
  cute + er -> cuter  
  house + ing -> housing

3) With the **y to i convention**, any suffix (vowel or consonant) can change a \<y\> at the end of a morpheme to \<i\>. You can only keep a final \<y\> inside a polymorphemic word if you have a good reason. There are only 3 good reasons.

  * If changing a \<y\> at the end of a morpheme to \<i\> forces an \<ii\> letter string, keep the \<y\>, and add the suffix. Example: cry + ing -> crying (not criing)
  * If the letter before the \<y\> is a vowel letter, keep the \<y\> and add the suffix. Example: stay + s -> stays
  * If the element on the right side of the join is another base, keep the \<y\> and add the base. Example: play + mate -> playmate

If you contribute to this project, please be sure to check the joins of your words sums and share the most accurate representation of morphemic structure as possible.

# Other considerations for building this knowledge base

The following best practices should be kept in mind when contributing a new base and its related word sums.

 * In the sum part of the equation where you're using the addition sign, use initial caps for all base elements while keeping prefixes, suffixes, and connecting vowel letters in all lowercase letters. This makes the word sums compatible with Neil Ramsden's Mini-Matrix Maker.
 * Do not include hyphenated words in any list of word sums. Hyphenated words belong in the etymological family for a base, not in the morphological family for a base. This is because a hyphenated word is closer to two words than to a single word.
 * Pairs like \<wolf\> and \<wolve\>, \<self\> and \<selve\>, \<loaf\> and \<loave\> are alternant morphemic forms. If one of these forms is the base that you are studying, its pair should have a separate morphological family.

# Getting ready to contribute

Anyone can contribute to this project using the following tools.

1. A GitHub account. Get yours at [github.com/join](https://github.com/join).
2. GitHub Desktop. Download it at [desktop.github.com](https://desktop.github.com).
3. The Atom text editor. Download it at [atom.io](https://atom.io).
4. The project files. The project homepage is [here](https://github.com/sallycole/sallycole.github.io).
5. Permission to commit code to the project. To request this, contact Sally Cole via email at S͟a͟l͟l͟y͟C͟o͟l͟e͟ at gma͟i͟l͟ d͟o͟t͟ ͟c͟o͟m͟ or via Twitter.

A tutorial video about getting setup with these tools is available [here on YouTube](https://youtu.be/sfIoTHWTkk8).

# How to format your contributions prior to committing them

This project stores data about English bases in a markdown file format that ends with .md. We use only one .md file per English base. Then, we use a human-readable data-serialization language called YAML within the file to store detailed information about each individual base. This includes whether the base is free or bound, the base's oldest known root, this root's language of origin, a denotation or primary meaning of the base, and all the word sums and words that can be built by adding affixes and connecting vowel letters to the base.

You can contribute by making new .md files for bases not yet contributed. Or, by checking the work of others and updating the .md files that they have contributed with more or better information.

When you make a new .md file, mimic the format below while replacing the data values with the relevant information for the base that you are working with.

```YAML
---
name: vide
title: vide
type: free
reference_link: https://www.etymonline.com/word/vide#etymonline_v_7775
root_name: videre
root_language: Latin
denotation: "see"
word_sums:
- sum: 'e + Vide + ence'
  respelling: evidence
- sum: 'pro + vide + ed'
  respelling: provided
- sum: 'pro + vide'
  respelling: provide
- sum: 'e + Vide + ent'
  respelling: evident
- sum: 'e + Vide + ent + ly'
  respelling: evidently
---
```

Please note that if you are putting a contraction such as the n't of don't into the value for a sum, you must type the apostrophe twice instead of once so as to adhere to the YAML code specification. For the respelling, you can type the apostrophe once per usual. Here is an example of that:

```YAML
  - sum: 'do + n''t'
    respelling: don't
```

If you've made a .md file and are not yet familiar enough with GitHub to check it in, feel free to put it in a .zip file and email it to sallycole at gmail dot com.

# Using word sums from this project to make word matrices

You can create a word matrix out of any group of word sums that you copy from this site. Just follow these steps.

1. Browse or search for a morphological base at [swi.storyhouracademy.com](https://swi.storyhouracademy.com).
2. Open the page for a base that interests you.
2. On the base's page, copy the bulleted list of word sums.
3. In another browser window, go to [Neil Ramsden's Mini Matrix-Maker](http://www.neilramsden.co.uk/spelling/matrix/temp/index.html).
4. Paste the word sums from this site into the big word sum field. Then, add in the other relevant info and click 'Update'.

# Researching a base and its morphological family of word sums

If you want to learn more about word sums, you'll want to explore the topics of Structured Word Inquiry (SWI) and orthographic phonology. Here are a few places to visit on your journey:

* [Peter Bowers and the WordWorks Literacy Center](http://wordworkskingston.com/WordWorks/Home.html) - Start with [this article](http://www.wordworkskingston.com/WordWorks/Structured_Word_Inquiry.html).
* [SWI Classes from See the Beauty of Dyslexia](https://www.seethebeautyindyslexia.com/swi-classes.html)
* [Real Spelling Spellinars](http://www.realspelling.fr/Welcome_to_Real_Spelling/Spellinars.html)
* [SWI Classes with Mary Beth Stevens](http://mbsteven.edublogs.org/swi-class/)
* [SWI Coaching with Rebecca Loveless](http://rebeccaloveless.com/)
* [Gina Cooke and Linguist-Educator Exchange](https://linguisteducatorexchange.com/) - Start with the archive of [posts about bases](https://linguisteducatorexchange.com/category/linguistic-evidence/morphology/bases/).
* [Word Nerdery by Ann Whiting](https://wordinquiry.wordpress.com/) - Start with [this article](https://wordinquiry.wordpress.com/2017/08/03/finding-our-way-in-the-world/).
* [Learning About Spelling by Sue Hegland](https://learningaboutspelling.com/) - Start with [this article](https://learningaboutspelling.com/2018/11/06/comprehending-spelling/).
* [Structured Word Inquiry in the Classroom on Facebook](https://www.facebook.com/groups/107360163171766/)
* [Structured Word Inquiry on Facebook](https://www.facebook.com/groups/StructuredWordInquiry/)

Enjoy!
