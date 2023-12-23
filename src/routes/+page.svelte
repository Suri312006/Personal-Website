<script lang='ts'>
    //@ts-ignore
    import * as THREE from 'three';
    //@ts-ignore
	import RINGS from 'vanta/dist/vanta.net.min';

    function vanta(rings: any) {
        RINGS({
            el: rings,
            THREE: THREE,
            color: 0x000000,
			backgroundColor: 0x111111,
        })
    }
</script>

<div class='h-[100vh]' use:vanta/>
