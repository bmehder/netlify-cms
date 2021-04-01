---
slug: about-this-cms
title: About This CMS
---
# Markdown

These posts are created through the **Netlify CMS** using **Markdown**. Markdown is an easier version of HTML and is stored as a text document in a folder in a project's GitHub repository with a *.md* file extension.

These markdown files can be used to populate other sites. For example, someone could add a blog post to their personal blog, and use the same file to publish the post on something like Medium.com.

Markdown is also being used by writers and journalists to take advantage of the file portability and benefits of version control when using in combination with Git/GitHub.

Netlify CMS is a frontend single page app (SPA) built with React. This CMS can send invitations to users by email, and these users can create, edit, and delete blog posts.

Users don't need a GitHub account to use the CMS. Authentication is handled by OpenAuth services like Google (or GitHub).

Collections can be created in order to set the fields, taxonomies, etc. for new blog posts.

The benefit is that there is no database storing content like traditional CMSs running on LAMP or MExN stacks.

This is a static website. Each blog post (Markdown file) is read and converted to HTML at build time. The build command is re-executed by Netlify each time a commit is pushed to GitHub.