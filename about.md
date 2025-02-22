---
layout: page
title: About
permalink: /about/
---

Hello and welcome to [wordsums.info](https://wordsums.info).

This is an open source project designed to collect word sums for all free and bound bases in Present-Day English.

# What is a base?

A base is a morpheme to which prefixes, suffixes, connecting vowel letters, or other bases may be added. A free base can stand alone as a word in English whereas a bound base can not. For example, \<do\> is a free base while \<pter\> is a bound base.

# What is a word sum?

A word sum is a hypothesis about the morphemic structure of a word. One way this type of hypothesis can be falsified is to apply suffixing conventions to the joins between each of the elements being added together. There are three suffixing conventions to check your joins with. These are:

1) With the **consonant doubling convention**, you must double the consonant letter of a base element if the following conditions are met:

  * There is a suffix that begins with a vowel letter being added to a base element.
  * The base element is a single, monosyllabic form. Or, it is a polysyllabic form whereby the final syllable of the base element is a stressed syllable in the word being built.
  * The base element ends with a vowel letter grapheme followed by a consonant letter grapheme, but not \<w\> or \<x\>.

  Examples:  
  cut + ing -> cutting  
  per + mit + ed -> permitted
  trepan + ing -> trepanning
  sew + ing -> sewing
  box + ing -> boxing
  orphan + ed -> orphaned

  Note that a consonant at the end of a prefix or suffix will never double. Only a consonant at the end of a base element may double.

  Also note that only a vowel suffix can force consonant doubling. A connecting vowel letter can not force consonant doubling.

2) With the **final e convention**, you must replace the final \<e\> in the morpheme on the left side of a join between two morphemes if the following conditions are met:

  * The final \<e\> is an orthographic marker and does not represent a phoneme.
  * The suffix on the right side of the join begins with a vowel letter.  

  Examples:  
  cute + er -> cuter  
  house + ing -> housing

3) With the **y to i convention**, any suffix (vowel or consonant) can change a \<y\> at the end of a morpheme to \<i\>. You can only keep a final \<y\> inside a polymorphemic word if you have a good reason. There are only 3 good reasons.

  * If changing a \<y\> at the end of a morpheme to \<i\> forces an \<ii\> letter string, keep the \<y\>, and add the suffix. Example: cry + ing -> crying (not criing)
  * If the letter before the \<y\> is a vowel letter, keep the \<y\> and add the suffix. Example: stay + s -> stays
  * If the element on the right side of the join is another base element, keep the \<y\> and add the base element. Example: ply + wood -> plywood

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

This project stores data about English bases in a markdown file format that ends with .md. We use only one .md file per English base. Then, we use a human-readable data-serialization language called YAML within the file to store detailed information about each individual base. This includes whether the base is free or bound, the base's oldest known root, this root's language of origin, a denotation or primary meaning of the base, an Etymonline root search link, an Etymonline base link, a Wiktionary base link, a Wiktionary root link, a courtesy of link, notes, all the word sums and words that can be built by adding affixes and other bases to the base, an image of the word matrix for the base, related bases, other relatives of the base, and other related images.

You can contribute by making new .md files for bases not yet contributed. Or, by checking the work of others and updating the .md files that they have contributed with more or better information. Or, by adding images related to a base.

When you make a new .md file, mimic the format below while replacing the data values with the relevant information for the base that you are working with.

```YAML
---
name: vide
title: vide
type: free
category: 4-letters
denotation: "see"
root_name: videre
root_language: Latin
etymonline_root_search_link: URL
etymonline_base_link: URL
wiktionary_base_link: URL
wiktionary_root_link: URL
courtesy_link:
- name: Site Name
  url: URL
note: <span>Write any special notes you have in HTML using the span tag.</span>
word_sums:
- sum: e + Vide + ence
  respelling: evidence
- sum: pro + Vide + ed
  respelling: provided
- sum: pro + Vide
  respelling: provide
- sum: e + Vide + ent
  respelling: evident
- sum: e + Vide + ent + ly
  respelling: evidently
word_matrix: /assets/letter/base-root.png
related_bases:
- name: a relative
  url: /bases/#-letters/base-root/
- name: a relative
  url: /bases/#-letters/base-root/
other_relatives:
- name: name
- name: name
other_images:
- image: /assets/letter/base_identifier.jpeg
---
```

If you've made a .md file and are not yet familiar enough with GitHub to check it in, feel free to put it in a .zip file and email it to sallycole at gmail dot com.

# Using word sums from this project to make word matrices

You can create a word matrix out of any group of word sums that you copy from this site. Just follow these steps.

1. Browse or search for a morphological base at [https://sallycole.github.io/](https://sallycole.github.io/).
2. Open the page for a base that interests you.
2. On the base's page, copy the bulleted list of word sums.
3. In another browser window, go to [Neil Ramsden's Mini Matrix-Maker](http://www.neilramsden.co.uk/spelling/matrix/temp/index.html).
4. Paste the word sums from this site into the big word sum field. Then, add in the other relevant info and click 'Update'.

# Researching a base and its morphological family of word sums

If you want to learn more about word sums, you'll want to explore the topics of Structured Word Inquiry (SWI) and orthographic phonology. Here are a few places to visit on your journey:

* [Peter Bowers and the WordWorks Literacy Center](http://wordworkskingston.com/WordWorks/Home.html) - Start with [this article](http://www.wordworkskingston.com/WordWorks/Structured_Word_Inquiry.html).
* [SWI Classes from See the Beauty of Dyslexia](https://www.seethebeautyindyslexia.com/swi-classes.html)
* [SWI Classes with Mary Beth Stevens](http://mbsteven.edublogs.org/swi-class/)
* [SWI Coaching with Rebecca Loveless](http://rebeccaloveless.com/)
* [Word Nerdery by Ann Whiting](https://wordinquiry.wordpress.com/) - Start with [this article](https://wordinquiry.wordpress.com/2017/08/03/finding-our-way-in-the-world/).
* [Learning About Spelling by Sue Hegland](https://learningaboutspelling.com/) - Start with [this article](https://learningaboutspelling.com/2018/11/06/comprehending-spelling/).

Enjoy!
