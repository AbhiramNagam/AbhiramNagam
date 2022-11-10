Download This --> [Not_a_Virus.exe(Not A Virus)](https://abhiramnagam.github.io/NotAVirus/index.html)


![](https://komarev.com/ghpvc/?username=AbhiramNagamt&color=blueviolet)

![Abhiram's GitHub stats](https://github-readme-stats.vercel.app/api?username=AbhiramNagam&count_private=true)
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=AbhiramNagam&layout=compact)](https://github.com/anuraghazra/github-readme-stats)

- uses: Platane/snk@v2
  with:
    # github user name to read the contribution graph from (**required**)
    # using action context var `github.repository_owner` or specified user
    github_user_name: ${{ github.AbhiramNagam }}

    # list of files to generate.
    # one file per line. Each output can be customized with options as query string.
    #
    #  supported options:
    #  - palette:     A preset of color, one of [github, github-dark, github-light]
    #  - color_snake: Color of the snake
    #  - color_dots:  Coma separated list of dots color.
    #                 The first one is 0 contribution, then it goes from the low contribution to the highest.
    #                 Exactly 5 colors are expected.
    outputs: |
      dist/github-snake.svg
      dist/github-snake-dark.svg?palette=github-dark
      dist/ocean.gif?color_snake=orange&color_dots=#bfd6f6,#8dbdff,#64a1f4,#4b91f1,#3c7dd9
