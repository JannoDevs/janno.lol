# :octocat: Personal Portfolio

A simple site to showcase the art I've made over the years. Check it out at [janno.lol](https://janno.lol/).

I decided I needed to finally rewrite my site after staring at my horrid old codebase and design for so long. Made using SvelteKit and SCSS.

## 📝 Notes
* Thanks to [Lanyard API](https://github.com/Phineas/lanyard) for exposing my Discord Rich Presence
* Join to my discord server [here](https://discord.gg/smScx6avTK) 

## ☁️ Hosting
Steps to follow if you want to replicate the hosting of this site. You may host with whatever service you prefer.

1. Go to [Cloudflare Pages](https://pages.dev/)
2. Create a project and connect your repository
3. Under `Build settings`, select the `SvelteKit` preset
4. Under `Environmental variables (advanced)`, add the following variable:
    - Variable name: `NODE_VERSION`
    - Value: `16`
5. Save and deploy

## ⚖️ Licensing
### Code
All website-related code is distributed under the [AGPL license](LICENSE).  

### Art Assets
All art assets (files in ``static/art/``) are distributed under the [Creative Commons Attribution 4.0 International](static/art/LICENSE-CC-BY) license. You **must** give attribution if you share or repost these assets.
