---
layout: page
title: "友链"
permalink: links.html
sequence: 5
---

<style>
  .most-valuable-link {
    margin-bottom: 1.2rem;
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    grid-template-rows: repeat(2, 1fr);
    grid-gap: 10px;
  }
  .most-valuable-link .mvl-link {
    display: flex;
    flex-direction: column;
    justify-content: center;
    position: relative;
    padding-left: 85px;
    height: 80px;
    width: 100%;
    color: inherit;
  }
  .most-valuable-link .mvl-link:hover {
    background-color: rgba(220, 50, 47, 0.1);
    border-bottom: 0;
  }
  .most-valuable-link .mvl-link img {
    position: absolute;
    top: 10px;
    left: 10px;
    margin-bottom: 0;
    width: 60px;
    height: 60px;
    border-radius: 50%;
  }
  .most-valuable-link .mvl-link h4 {
    margin: 0 0 10px 0;
    line-height: 1.2rem;
  }
  .most-valuable-link .mvl-link div {
    font-size: 0.9rem;
    line-height: 1.2rem;
    white-space: nowrap;
    overflow: hidden;
    text-overflow: ellipsis;
  }
</style>

<section class="most-valuable-link">
  <a class="mvl-link" href="/">
    <img src="/public/images/me.jpg">
    <h4>饮冰先生</h4>
    <div>https://github.com/myanbin/myanbin.github.io</div>
  </a>
  <a class="mvl-link" href="/">
    <img src="/public/images/me.jpg">
    <h4>虚位以待</h4>
    <div>这个家伙很懒，什么东西都没有留下。</div>
  </a>
  <a class="mvl-link" href="/">
    <img src="/public/images/cat.jpg">
    <h4>虚位以待</h4>
    <div>这个家伙很懒，什么东西都没有留下。</div>
  </a>
</section>
