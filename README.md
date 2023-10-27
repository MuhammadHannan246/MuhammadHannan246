- 👋 Hi, This is Muhammad Hannan
- 👀 I've Skills in Java, Python, C++, C, Embedded C, Wordpress, HTML, CSS, JavaScript, JQuery, React.js, PHP, Laravel, Flutter  and Internet of Things(IoT)
- 🌱 I’m Currently Studying Computer Engineering
- 💞️ I’m Looking To Collaborate On New Projects.
- 📫 You Can Reach Me By:
- Email: sheikh.hannan06@gmail.com
- LinkedIn: https://www.linkedin.com/in/muhammad-hannan-81832a217 

<!---
MuhammadHannan246/MuhammadHannan246 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

- uses: Platane/snk@v3
  with:
    # github user name to read the contribution graph from (**required**)
    # using action context var `github.repository_owner` or specified user
    github_user_name: ${{ github.repository_owner }}

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
