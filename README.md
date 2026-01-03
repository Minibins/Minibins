<h2>About Me</h2>

<p>
Hi! My name is Maksym. I am <span id="age"></span> years old and I am from Ukraine.
</p>

<p>
I am a C# developer with previous experience in Unity.  
I am interested in game engines, graphics programming, and building my own tools and systems.
</p>

<script>
  const birthDate = new Date("2009-12-03");
  const today = new Date();

  let age = today.getFullYear() - birthDate.getFullYear();
  const m = today.getMonth() - birthDate.getMonth();

  if (m < 0 || (m === 0 && today.getDate() < birthDate.getDate())) {
    age--;
  }

  document.getElementById("age").textContent = age;
</script>



<b>My GitHub Stats</b>

<a href="http://www.github.com/Minibins"><img src="https://github-readme-stats.vercel.app/api?username=Minibins&show_icons=true&hide=&count_private=true&title_color=0891b2&text_color=ffffff&icon_color=0891b2&bg_color=1c1917&hide_border=true&show_icons=true" alt="Minibins's GitHub stats" /></a>

<a href="http://www.github.com/Minibins"><img src="https://github-readme-streak-stats.herokuapp.com/?user=Minibins&stroke=ffffff&background=1c1917&ring=0891b2&fire=0891b2&currStreakNum=ffffff&currStreakLabel=0891b2&sideNums=ffffff&sideLabels=ffffff&dates=ffffff&hide_border=true" /></a>

<a href="https://github.com/Minibins" align="left"><img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Minibins&langs_count=10&title_color=0891b2&text_color=ffffff&icon_color=0891b2&bg_color=1c1917&hide_border=true&locale=en&custom_title=Top%20%Languages" alt="Top Languages" /></a>

</ul>
