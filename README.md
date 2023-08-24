# [Wowchemy Block Starter Template](https://github.com/wowchemy/wowchemy-block-starter)

**Looking to build and publish a [Wowchemy Block](https://wowchemy.com/blocks/) that doesn’t exist yet?**

_[**Wowchemy**](https://wowchemy.com) makes it easy to create a beautiful website for free. Edit your site in Markdown, Jupyter, or RStudio, generate it with Hugo, and deploy with GitHub or Netlify. Customize anything on your site with blocks, themes, and language packs._

## 🌈 Add the Block to your Site

1. Install the block by referencing it in your `config/_defaults/config.yaml`:
   ```yaml
   module:
     imports:
       # Your block's GitHub URL (replace <USERNAME> and <COLLECTION-NAME> with your GitHub username and block collection name)
       - path: github.com/<USERNAME>/wowchemy-block-<COLLECTION-NAME>
   ```
1. Create an instance of your block in `home/`, for example let's create `home/my-block.md`:
   ```markdown
   ---
   sections:
     - block: gallery
       content:
          title: Facilities
          # subtitle: Section subtitle
          # text: Section text
          items:
            - name: Computer
              description: do computing
              img: facilities/computer.jpg
            - name: Laser Tube
              description: gen laser
              img: facilities/computer.jpg
            - name: Printer
              description: print
              img: facilities/computer.jpg
   ```

## 📢 Share your block

Add the [wowchemy-hugo-extension](https://github.com/topics/wowchemy-hugo-extension) tag to your block's GitHub repository to help other users find it.

Share your block with the community on [Discord](https://discord.gg/z8wNYzb) and [Twitter](https://twitter.com/intent/tweet?text=I%27m%20creating%20a%20beautiful%20website%20section%20using%20the%20free%20%E2%9D%A4%EF%B8%8F%2C%20open%20source%20%40wowchemy%20Website%20Builder%20for%20%40GoHugoIO%20by%20%40GeorgeCushen%20%E2%9C%A8%20Have%20some%20feedback%3F%20Please%20comment%20%F0%9F%A4%97&hashtags=MadeWithWowchemy&url=https://wowchemy.com/).
