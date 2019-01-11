# glaciate-blog
Repository for the blog posts for https://www.glaciate.net

# How to Add Posts
Each post is structured as

```
> slug game-assignment-elevator-pitch
> title Game Assignment: Elevator Pitch
> date 1 Feb 2017
> tags gamedev, university, gamedev-assignment
---
{blog post}
```

**slug**: the URL that will be used for the blog post. Should not be changed once set unless if it really needs to, otherwise you risk breaking existing links and causing SEO issues.

**title**: the title that will be used for the blog post.

**date**: the date the blog post will display on the blog. Can be in any Javascript-readable format, but stick to `dd MMM YYYY` as a convention.

**tags**: a comma separated list of tags that will display on the blog. Used to sort posts.

The metadata section is parsed and removed from the final rendered blog post and will be used to build up an index at runtime.

# Possible Future (Re)Additions
**sail image**: makes things look pretty? Need to source a load of images first before considering reimplementing this.

**author**: should others ever want/need to post, this might be needed as metadata

???
