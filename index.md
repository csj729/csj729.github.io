# Postick Development log

안녕하세요! 게임 개발자 **Postick**의 개발 일지입니다.
이곳에는 개발 과정, 기술 공유, 그리고 잡담이 올라올 예정입니다.

---

## 📝 최신 글 목록

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <span style="color: #888; font-size: 0.8em;"> - {{ post.date | date: "%Y.%m.%d" }}</span>
    </li>
  {% endfor %}
</ul>
