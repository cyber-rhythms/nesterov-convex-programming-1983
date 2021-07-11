# nesterov-convex-programming-1983

The following repository contains my work-in-progress, computer-assisted English translation of the following paper, originally published in Russian:

[Nesterov, Y. E. (1983). A method of solving a convex programming problem with convergence rate O(1/k^2). (Russian). *Doklady Akademii Nauk SSSR, 269*(3), 543–547.](http://www.mathnet.ru/php/archive.phtml?wshow=paper&jrnid=dan&paperid=46009&option_lang=eng)

<p align="center">
    <a href="http://www.mathnet.ru/php/archive.phtml?wshow=paper&jrnid=dan&paperid=46009&option_lang=eng">
        <img src="nesterov.png">
    </a>
</p>

Some remarks about the rationale for uploading an English translation of this paper. My studies in deep learning covered a well-known technique known as *Nesterov's accelerated gradient method*, which originated in the above paper. Personally, reading or attempting to read the original source of a method helps me anchor the ideas, and so I sought a copy to read. While this paper is freely available and easily accessible online at the above link, it is in Russian.

According to [Alexandre Eremenko](https://mathoverflow.net/users/25510/alexandre-eremenko)in [this thread](https://mathoverflow.net/questions/395374/nesterov-1983-paper-translation-from-russian-to-english) at MathOverflow, an English translation of this paper exists with the following reference:

Nesterov, Yu. E. A method of solving a convex programming problem with convergence rate 0(1/k2). (English. Russian original) Zbl 0535.90071 Sov. Math., Dokl. 27, 372-376 (1983); translation from Dokl. Akad. Nauk SSSR 269, 543-547 (1983).

And it is available through interlibrary loan. However, this is difficult for me to get hold of where I live.

Despite this work having had a fair number of citations, as well as a strong influence on the convex optimisation and deep learning literature, it seems a strange state of affairs that it is not available in English online.

This repository aims to remedy that state of affairs.

## Directory structure.

1. `nesterov-method-convex-english-1983.md` - work-in progress English translation in Markdown format.

2. `nesterov-method-convex-english-1983.pdf` - work-in progress English translation in PDF format.

## Computer-assisted translation and roadmap.

I do not speak Russian, nor can I read Cyrillic. I also do not have deep technical proficiency with the mathematics of convex optimisation. However, I do possess some mathematical literacy, and hope to use this opportunity to learn more about the technique, and to delve more deeply into introductory convex optimisations.

Following a suggestion by [Sean Eberhard](https://mathoverflow.net/users/20598/sean-eberhard) on MathOverflow, I decided to use a combination of [DeepL](https://www.deepl.com/translator) and [Google Translate](https://translate.google.com/) to supply a first approximation of an English translation.

My contributions, hopefully with assistance from a community, would be to proofread and appropriately render the translation output by DeepL and Google Translate into clear readable English prose. It is also envisaged that a degree of technical proofreading will need to be undertaken, both in parsing the mathematical definitions, arguments and proofs; and in the selection of appropriate technical vocabulary. Lastly, some choices need to be made on notation and typesetting.

Here is a roadmap:

1. Computer translate the document using DeepL and Google Translate, and port to PDF using Pandoc - **completed**.

2. Check fidelity of mathematical transcription of original manuscript - **mostly completed**.

3. Render prose from computer translation into clear, readable English prose.

4. Update formatting e.g. paragraphing.

5. Technical proof-reading, consisting of parsing the mathematical arguments for correctness and possible typos in the original manuscript. Appropriate translation of technical terms will need to be checked.

6. Decisions on updating some of the notation.

7. Typeset in LaTeX. Currently working in Markdown because I prefer it to LaTeX. LaTeX files will be uploaded soon.

8. Author, journal and any other copyright holder permissions - **pending.**

9. Conditional on receipt of copyright holder permissions, publish on arXiv.

## Contributing to this project.

Both prose readability suggestions, or technical assistance with proofreading the the mathematics are not only welcome, but actively solicited. In particular, technical proficiency with convex optimisation would be *extremely helpful*.

If you wish to contribute, please submit an issue.










