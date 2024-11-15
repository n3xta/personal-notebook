[toc]

---

# What If Assignment

## the 'world'

LEC (Life Emotion Capsules) are a speculative product designed to restore authentic human emotions in individuals who have become emotionally numb due to the pervasive influence of AI and social media feedback loops. The capsules serve as a means to rekindle genuine feelings in a society where emotional capacity has diminished.

The LEC exists in a near-future world where technology dominates daily life. AI algorithms curate experiences to the point where people are trapped in echo chambers, and social media interactions have replaced meaningful human connections. In this society, emotional depth is rare, and people struggle to experience true feelings without artificial assistance.

<img src="https://raw.githubusercontent.com/n3xta/image-hosting/main/img/202411150019994.png"/>

## Research training models

I'm choosed to use Stable Diffusion. Stable Diffusion is an open-source model that gained popularity last year. Because it's open-source, others can fine-tune and retrain it, leading to the development of a vast community. Its results might not be as good as Midjourney or DALL·E, but I choose to use it because I really appreciate the open-source community atmosphere. Anything you need can be found:

- A convenient GUI - I use Comfy UI, it's a node based UI for stable diffusion models, that makes your ai generating process feels like touchdesigner.
- A styled model - I use `Realistic Vision V6.0 B1`, because I want to generate product-design-like images. 
- Some flavoring (They call them LoRAs) - I use 
- Any detail tweaking - Since it is open sourced I can edit every parameter in it.

### Communities & online resources

https://www.shakker.ai/

This one is more for commercial use. I personally like this better. It's more organized and contains higher quality models. 

https://civitai.com/

This is the OG when stable diffusion first came out. This one is more for recreational use such as generating illustrations for your oc or sth. 

## Process

Since everything runs locally and openly, the setup is a bit different from using commercial products such as midjourney, in which the product developers are trying their best to make the whole workflow easiest. 

So I will have to run ComfyUI first using my terminal:

<img src="https://raw.githubusercontent.com/n3xta/image-hosting/main/img/202411150105243.png"/>

<img src="https://raw.githubusercontent.com/n3xta/image-hosting/main/img/202411150105971.png"/>

<img src="https://raw.githubusercontent.com/n3xta/image-hosting/main/img/202411150106847.png"/>

Then, I can use my models and LoRAs in a relatively straightforward node view. I remembered that a year ago we were still using something called WebUI, in which you will have to deal with a lot of text and commands.

### My Workflow:

<img src="https://raw.githubusercontent.com/n3xta/image-hosting/main/img/202411150112707.png"/>

This is an overview of my nodes, and each one represents a parameter / plugin. 

My screen looks like this when generating:

<img src="https://raw.githubusercontent.com/n3xta/image-hosting/main/img/202411150200719.png"/>

I tried different models and LoRAs, for example:

<img src="https://raw.githubusercontent.com/n3xta/image-hosting/main/img/202411150113748.png"/>

<img src="https://raw.githubusercontent.com/n3xta/image-hosting/main/img/202411150113225.png"/>

And if you struggle with prompts:

<img src="https://raw.githubusercontent.com/n3xta/image-hosting/main/img/202411150132014.png"/>

find prompts on amazon.

#### Example of one image: 

> A transparent glass bottle filled with capsules of various vibrant colors, resting on a sleek surface against a minimalist background; sharp focus, high detail, soft lighting, vivid colors, photorealistic, minimalistic design

<img src="https://raw.githubusercontent.com/n3xta/image-hosting/main/img/202411150127441.png"/>

then I replaced it with a simpler version.

> pills in a bottle, filled with (pills) of various soft colors, resting on a sleek surface; soft lighting, photorealistic,

<img src="https://raw.githubusercontent.com/n3xta/image-hosting/main/img/202411150128115.png"/>

Still weird.

I tried several times and found this works well: 

> A transparent plastic_bottle, filled with pills of various soft colors, resting on a sleek surface against a minimalist background, high detail, soft lighting, photorealistic, minimalistic design, hitech, warm

<img src="https://raw.githubusercontent.com/n3xta/image-hosting/main/img/202411150131789.png"/>

<img src="https://raw.githubusercontent.com/n3xta/image-hosting/main/img/202411150133381.png"/>

I really want to combine the effect of these two images. So I added weight to several text prompts: 

<img src="https://raw.githubusercontent.com/n3xta/image-hosting/main/img/202411150135535.png"/>

And at last I found the perfect fit:

<img src="https://raw.githubusercontent.com/n3xta/image-hosting/main/img/202411150156112.png"/>

#### Sometimes You Need Happy Accidents

<img src="https://raw.githubusercontent.com/n3xta/image-hosting/main/img/202411150136008.png"/>


## Yapping

I have a lot to say about it. I never and won't use it to create illustrations because it makes me lose the meaning of drawing them myself. (I draw, simply because I enjoy the process of creation.) However, I harbor much less hostility toward it than many traditional media artists do. In the summer of 2023, when I first saw an entire wall of AI-generated commercial advertising posters in a Shanghai subway station, I was so disgusted I wanted to vomit. This intense feeling of nausea made me realize one thing—the art jobs that can be replaced by AI aren't truly "creative" work. Before the emergence of generative AI, these artworks—commercial ads outsourced layer upon layer to unknown small workshops, assembly-line 2D pornographic illustrations, mass-produced graffiti printed on phone cases or canvas bags—didn't possess artistic value in themselves; they were the cheapest works money could buy. After realizing this, I let go of my defensive attitude toward generative AI.

Over the past year, I've found that most consumers in the market don't need "artistic value" at all. Those who used to argue—the AI enthusiasts who said AI is a "sewing machine" that will replace traditional artists, the "textile workers"; and the artists who said AI is "corpse stitching," a "cancer"—both sides have discovered they are essentially insignificant! Outside their battlefield, no one cares about them. In some ways, they sympathize with each other because they're both pitiable souls who mistakenly believe their creations have great value. In fact, there are still people pouring money into the NFT market, buying some incredibly ugly digital works. They're just enjoying the purchase of products with hyped cultural attributes, as if that means they aren't falling into the trap of consumerism. There are still people commissioning private artworks, just for brand value, so they can own a piece by some internet-famous artist, regardless of what tools or software the artist uses. There are still people using canvas bags with oil painting designs, completely unaware that the artwork on their bag is now AI-generated, because all they need is a bag with a different style. The funniest thing is that the vast majority of internet users still have no concept of copyright, casually stealing images online to use as their avatars or wallpapers. You can't even criticize them because they're stealing AI-generated images.

Anyways thank you for reading this.