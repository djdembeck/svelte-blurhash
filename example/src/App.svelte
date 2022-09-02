<script>
        import { BlurhashImage, BlurhashPicture } from "svelte-blurhash";
</script>

<div>
        <BlurhashPicture
                src={"https://www.1-firststep.com/samplephp/jpg-webp-avif/image/1000.jpg"}
                hash={"LEHV6nWB2yk8pyoJadR*.7kCMdnj"}
                width={320}
                height={206}
                fadeDuration={800}
        >
                <source
                        srcset="https://www.1-firststep.com/samplephp/jpg-webp-avif/image/1000.avif"
                        type="image/avif"
                />
        </BlurhashPicture>

        <BlurhashImage
                src={"https://blurha.sh/12c2aca29ea896a628be.jpg"}
                hash={"LEHV6nWB2yk8pyoJadR*.7kCMdnj"}
                width={320}
                height={206}
                fadeDuration={800}
        />

        <BlurhashImage
                src={"https://blurha.sh/e08adedc9f82ade9f9d5.jpg"}
                hash={"LGF5]+Yk^6#M@-5c,1J5@[or[Q6."}
                width={320}
                height={206}
        />

        <BlurhashImage
                src={"https://blurha.sh/2af1b155f29d7089e3d9.jpg"}
                hash={"L6Pj0^i_.AyE_3t7t7R**0o#DgR4"}
                width={320}
                height={206}
        />

        <BlurhashImage
                src={"https://blurha.sh/ea9e499f8080ce9956a8.jpg"}
                hash={"LKO2?U%2Tw=w]~RBVZRi};RPxuwH"}
                width={320}
                height={206}
                fadeDuration={2000}
        />
</div>

<div>
        <a href="https://github.com/h416/svelte-blurhash/tree/master/example"
                >source</a
        >
</div>

<style>
        :global(img) {
                vertical-align: bottom;
        }
</style>
