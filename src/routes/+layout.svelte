<script>
  import "../app.css";
</script>


<h1 class="text-3xl font-bold underline">
  Hello world!
</h1>

<nav>
	<a href="/about">メッセージ</a>
	<a href="/business">主要事業</a>
  <a href="/products">取扱商品</a>
  <a href="/company">会社概要</a>
  <a href="/organization">組織図</a>
</nav>

<slot></slot>

<style lang="postcss">
  :global(html) {
    background-color: theme(colors.gray.100);
  }
</style>