<!-- TITLE: Home -->
<!-- SUBTITLE: A quick summary of Home -->

# Teste de página inicial
## Teste de heading
ok, um doi três
`um código aqui`

[video](https://www.youtube.com/watch?v=NPpftnFok2Q){.video}

![Screen Shot 2019 06 11 At 10 19 21](/uploads/pasta-de-teste/screen-shot-2019-06-11-at-10-19-21.png "Screen Shot 2019 06 11 At 10 19 21")

```html
<template>
    <div 
            id="tainacan-admin-app" 
            class="columns is-fullheight"
            :class="{ 
                'tainacan-admin-iframe-mode': $route.query.iframemode, 
                'tainacan-admin-read-mode': $route.query.readmode
            }">
        <template v-if="activeRoute == 'HomePage'">
            <tainacan-header />
            <router-view /> 
        </template>
    </div>
</template>
```



