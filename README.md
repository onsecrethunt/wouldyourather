
---

### 5. README.md for **wouldyourather.cc**

```markdown
# WouldYouRather.cc

A fun site to get random "Would You Rather" questions for games and icebreakers.

## How it works

JavaScript randomly picks a question from an array and displays it.

### Demo snippet

```html
<button onclick="showQuestion()">Show Question</button>
<div id="question"></div>

<script>
const questions = [
  "Would you rather fly or be invisible?",
  "Would you rather have a pet dragon or a pet unicorn?",
  "Would you rather live in the city or the countryside?"
];

function showQuestion() {
  const index = Math.floor(Math.random() * questions.length);
  document.getElementById('question').textContent = questions[index];
}
</script>
