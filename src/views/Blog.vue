<template>
  <div>
    <section class="page-upper">
      <h1 class="page-upper__title">Blog Posts</h1>
    </section>
    <main class="container">
        <!-- <?php foreach($blogPosts as $blogPost):?>
            <article class="blog-post">
                <a class="blog-post__link" href="<?= $blogPost->url;?>">
                        <time class="blog-post__date desktop-hide">
                            <?= $blogPost->excerptDate;?>
                        </time>
                        <time class="blog-post__date desktop-show">
                            <?= $blogPost->date;?>
                        </time>
                        <h3 class="blog-post__title">
                            <?= $blogPost->title;?>
                        </h3>
                        <p class="blog-post__excerpt">
                            <?= substr($blogPost->content, 0, 200) ;?>
                        </p>
                    </a>
                    <div class="blog-post__tags">
                        <?php foreach($blogPost->tags as $tag):?>
                            <div class="blog-post__tag">
                                <?= $tag;?>
                            </div>
                        <?php endforeach;?>
                    </div>
                <hr class="blog-post__separator">
            </article>
        <?php endforeach;?> -->
    <img class="doodle doodle--blog" src="assets/illustrations/doodle4.svg">
  </div>
</template>

<script>
export default {

}
</script>

<style>

</style>