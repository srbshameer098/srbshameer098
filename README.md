from pathlib import Path

path = Path("/mnt/data/README.md")
readme = path.read_text(encoding="utf-8")

old = '''## 📊 GitHub Analytics

<div align="center">

<a href="https://github.com/srbshameer098">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=srbshameer098&show_icons=true&theme=tokyonight&hide_border=true&rank_icon=github" alt="Shameer's GitHub stats" />
</a>
<a href="https://github.com/srbshameer098">
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=srbshameer098&layout=compact&theme=tokyonight&hide_border=true" alt="Most used languages" />
</a>

<br/>

<img width="70%" src="https://streak-stats.demolab.com?user=srbshameer098&theme=tokyonight&hide_border=true" alt="GitHub contribution streak" />

</div>
'''
new = '''## 📊 GitHub Analytics

<div align="center">

<a href="https://github.com/srbshameer098">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=srbshameer098&show_icons=true&theme=tokyonight&hide_border=true&rank_icon=github&include_all_commits=true" alt="Shameer's GitHub stats" />
</a>
<a href="https://github.com/srbshameer098">
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=srbshameer098&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" alt="Most used languages" />
</a>

<br/>

<img width="70%" src="https://streak-stats.demolab.com?user=srbshameer098&theme=tokyonight&hide_border=true" alt="GitHub contribution streak" />

</div>

## 🏆 GitHub Trophies

<div align="center">

<img src="https://github-profile-trophy.vercel.app/?username=srbshameer098&theme=tokyonight&no-frame=true&no-bg=true&margin-w=8&row=2&column=4" alt="GitHub profile trophies" />

</div>

## 🏅 Profile Badges

<div align="center">

[![Followers](https://img.shields.io/github/followers/srbshameer098?style=for-the-badge&logo=github&label=Followers&color=20C997)](https://github.com/srbshameer098?tab=followers)
[![Stars](https://img.shields.io/github/stars/srbshameer098?style=for-the-badge&logo=github&label=Total%20Stars&color=F1C40F)](https://github.com/srbshameer098?tab=repositories)
[![Repositories](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/users/srbshameer098&query=$.public_repos&label=Public%20Repos&style=for-the-badge&logo=github&color=2F80ED)](https://github.com/srbshameer098?tab=repositories)
[![Profile Views](https://komarev.com/ghpvc/?username=srbshameer098&style=for-the-badge&color=8A2BE2&label=Profile%20Views)](https://github.com/srbshameer098)

</div>

## 📅 Contribution Activity

<div align="center">

[![Contribution Graph](https://github-readme-activity-graph.vercel.app/graph?username=srbshameer098&theme=tokyo-night&hide_border=true&area=true)](https://github.com/srbshameer098)

</div>
'''
if old not in readme:
    raise ValueError("Analytics section not found; README left unchanged.")
path.write_text(readme.replace(old, new), encoding="utf-8")
print(f"Updated analytics, trophies, badges, and contribution graph in {path}")
