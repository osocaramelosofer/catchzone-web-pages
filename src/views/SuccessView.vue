<script setup lang="ts">
import {CheckmarkCircleOutline} from "@vicons/ionicons5"
import { Icon } from "@vicons/utils"
</script>
<template>
    <div class="success-container">
        <div>
            <div class="center">
                <Icon size="100" color="green">
                    <CheckmarkCircleOutline/>
                </Icon>
            </div>
            <h2>Thanks for subscribing to catch zone</h2>
        </div>
         
    </div>
</template>
<style scoped>
.parent{

}
.success-container{
    width: 100%;
    height: 100%;
    display: flex;
    align-items: center;
    justify-content: center;
    
}
.center{
    display: flex;
    align-items: center;
    justify-content: center;
}
</style>