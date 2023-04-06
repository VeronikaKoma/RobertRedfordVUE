<script>
import RawHtmlData from '../components/myComponents/RawHtmlData.vue';
import SingleComponent from '../components/myComponents/SingleComponent.vue'

export default {components: { SingleComponent, RawHtmlData } };
</script>


<template>
    <div>
        <h1>Biografia de Robert Redford</h1>
        
        <h3>Charles Robert Redford nació un 18 de agosto de 1937 en la ciudad de Santa Mónica, en California. 
            Su padre, Charles Redford, era contador de la empresa Standard Oil y su mamá, Martha Hart, era ama de casa. 
            Ella ya tenía un hijo de otro matrimonio anterior, William Coomber.
            
            Robert contaba: "Mi familia es de origen irlandés - escocés.
            Ellos vinieron del viejo mundo y trajeron consigo el amor por las palabras y el placer de contar historias, 
            pero también llevaban consigo un absoluto rechazo acerca de hablar sobre cuestiones personales y un fuerte estoicismo 
            para enfrentar la adversidad. Ellos nunca jamás se quejaron de algo. 
            Yo tuve que encontrar la manera de dejar las emociones, porque sea cual fuere la emoción que sintieras, 
            éstas no eran invitadas a la mesa familiar".</h3>
            ---------------------------------------------------------------------
            <SingleComponent />
            ------------------------------------------------------------------------
            <RawHtmlData />
    </div>
</template>


<style lang="css" scoped>
h1{
    color: blueviolet;
}
</style>