<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:03045E,100:00B4D8&height=170&section=header&text=Profile%20README%20Starter&fontSize=44&fontColor=ffffff&desc=Make%20your%20GitHub%20profile%20look%20great%20in%2010%20minutes&descAlignY=72&descSize=16" alt="Profile README Starter" />
</p>

<p align="center">
  <b>A copy-and-paste guide for CS beginners.</b><br/>
  No coding needed. If you can copy, paste, and edit text, you can do this. 🙌
</p>

---

## 🤔 What is this?

When someone (a recruiter, a classmate, a hackathon teammate) clicks your GitHub name, they land on your **profile page**.
By default it's pretty empty. A **profile README** is a little intro page that shows up at the top of it, like this:

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:03045E,100:00B4D8&height=120&section=header&text=Alex%20Rivera&fontSize=40&fontColor=ffffff" width="520" /><br/>
  <sub>☝️ That banner is part of one. You'll make your own in a few minutes.</sub>
</p>

It's your first impression on GitHub. Even with zero projects, a clean intro makes you look like you know what you're doing.

> 📖 **Quick word guide**
> - **Repository (repo):** a folder that lives on GitHub.
> - **README.md:** a text file GitHub shows on the page automatically. The `.md` means it's written in *Markdown*, a simple way to format text.
> - **Commit:** GitHub's word for "save".

---

## 🚀 Step-by-step

### Step 1: Make a special repo

1. Log in to [github.com](https://github.com).
2. Click the **+** in the top-right corner → **New repository**.
3. For **Repository name**, type your GitHub username **exactly** (same capitals too).
   GitHub will show a message saying it's a ✨ *special* ✨ repository. That means you did it right.
4. Choose **Public**.
5. Check ✅ **Add a README file**.
6. Click **Create repository**.

> ⚠️ If you don't see the "special repository" message, the name doesn't match your username. Double-check the spelling.

### Step 2: Open the README for editing

On your new repo's page, click **README.md**, then click the ✏️ **pencil icon** (top-right of the file) to edit it.
Delete everything that's already in there.

### Step 3: Copy the template

Open **[`TEMPLATE.md`](TEMPLATE.md)** in this repo and click the **📋 Copy raw file** button (top-right of the file, next to "Raw").
Paste it into your README.

### Step 4: Fill in your info

Replace everything written in **CAPITAL LETTERS** with your own info. The [section guide](#-what-each-part-does) below explains every part.
Click the **Preview** tab at the top of the editor anytime to see how it looks.

### Step 5: Save it

Click the green **Commit changes...** button → **Commit changes** again.
Go to `github.com/YOUR-USERNAME` and admire your new profile. 🎉

---

## 🧩 What each part does

### 1. The banner

```html
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:03045E,100:00B4D8&height=160&section=header&text=YOUR%20NAME&fontSize=48&fontColor=ffffff" />
```

Change `YOUR%20NAME` to your name.
🔑 **Rule:** you can't put normal spaces inside a link, so every space becomes `%20`.

| You want | You type |
|---|---|
| Jane Doe | `Jane%20Doe` |
| Maria Lopez Garcia | `Maria%20Lopez%20Garcia` |

### 2. The typing animation

```html
<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&color=48CAE4&center=true&width=600&lines=LINE+ONE;LINE+TWO;LINE+THREE" />
```

This types out sentences one by one. Edit the part after `lines=`.
🔑 **Rules:** spaces become `+`, and a `;` starts the next sentence.

| You want | You type |
|---|---|
| CS student at NYU | `CS+student+at+NYU` |
| Two lines: "Hi there" then "I like Python" | `Hi+there;I+like+Python` |

> 💡 Keep each line short (under ~45 characters) so it fits.

### 3. About you

Plain text. Just write like you're introducing yourself in class:

```md
### 👋 Hey, I'm Jane
Freshman studying CS at State University. I like building small games and learning web dev.
```

**Nothing to say yet?** That's normal for freshmen! Try:
- 🔭 Working on: *"my intro to CS assignments"* or *"learning Python"*
- 🌱 Learning: *"Python, Git, HTML/CSS"*
- 💬 Ask me about: *"anime, chess, basketball, music"* (it doesn't have to be about code!)

### 4. Projects

A table of your projects. Each row has a link and a one-line description.

```md
| [Tic Tac Toe](https://github.com/janedoe/tic-tac-toe) | A two-player game I built in Python |
```

**No projects yet?** Delete the whole Projects section for now and add it back later.
Class assignments count too (just check that your professor is okay with them being public).

### 5. Tech icons

```html
<img src="https://skillicons.dev/icons?i=py,java,git" />
```

List the tools you've used, separated by commas, **no spaces**. Common ones:

| Tool | Code | | Tool | Code |
|---|---|---|---|---|
| Python | `py` | | HTML | `html` |
| Java | `java` | | CSS | `css` |
| C++ | `cpp` | | JavaScript | `js` |
| C | `c` | | React | `react` |
| Git | `git` | | VS Code | `vscode` |
| GitHub | `github` | | Linux | `linux` |

Full list: [skillicons.dev](https://github.com/tandpfun/skill-icons#icons-list). Only list things you've actually used. 😉

### 6. Stats

```html
<img src="https://streak-stats.demolab.com?user=USERNAME&theme=tokyonight&hide_border=true" />
```

Replace `USERNAME` with your GitHub username. It shows how many days in a row you've contributed, which is a fun way to stay consistent.

### 7. Links

```md
[LinkedIn](https://linkedin.com/in/YOUR-LINKEDIN) · [Email](mailto:YOU@EMAIL.com)
```

The text in `[brackets]` is what people see. The link in `(parentheses)` is where it goes.
Don't have a portfolio site? Just delete that link.

---

## 🎨 Make it yours

Want different colors? Swap the color codes (`03045E`, `00B4D8`, `48CAE4`) for any of these:

| Vibe | Banner colors | Typing color |
|---|---|---|
| 🌊 Ocean (default) | `0:03045E,100:00B4D8` | `48CAE4` |
| 🌅 Sunset | `0:FF5F6D,100:FFC371` | `FF8C69` |
| 🌸 Pastel | `0:C9B6FF,100:FFC8DD` | `B392F0` |
| 🌲 Forest | `0:134E5E,100:71B280` | `71B280` |
| 🖤 Mono | `0:0D1117,100:434343` | `C9D1D9` |

More ideas: [`CHEATSHEET.md`](CHEATSHEET.md). To see a finished one, check [`EXAMPLE.md`](EXAMPLE.md).

---

## 🆘 Something's wrong?

| Problem | Fix |
|---|---|
| My README doesn't show on my profile | The repo name must **exactly** match your username, and the repo must be **Public**. |
| An image shows as a broken icon | There's probably a normal space in the link. Change it to `%20` (banner) or `+` (typing). |
| My text shows up as `###` | Make sure there's a space after the `#` (`### Hello`, not `###Hello`). |
| The table looks broken | Every row needs the same number of `\|` characters. |
| The stats card is blank | It can take a minute. Double-check the username spelling. |

---

## ✅ Tips to stand out

- **Keep it short.** People skim. 3 to 5 sections is plenty.
- **Pin your best repos.** On your profile, click **Customize your pins**.
- **Add a profile picture.** A real photo or a nice avatar, not the default.
- **Update it every semester** as you learn new things and build new projects.

---

<p align="center">
  Found this helpful? Click the ⭐ at the top of this page and share it with a friend!<br/>
  <sub>Made with 💙 for CS beginners by <a href="https://github.com/httpsdluc">@httpsdluc</a></sub>
</p>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00B4D8,100:03045E&height=100&section=footer" width="100%" />
