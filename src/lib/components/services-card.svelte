<script>
// @ts-nocheck

    import Card from "$lib/components/card.svelte";
      // Import Swiper Svelte components
  import { Swiper, SwiperSlide } from 'swiper/svelte';

// Import Swiper styles

</script>

<style >
    @import "$lib/styles/services-card.styles.css";
    @import"swiper/css";
</style>

<div id="services-card-container">
    <div id="services-card-title">Serviços</div>
    <div id="line2"></div>

    <div id="swipper-container">
        <Swiper id="swipper-custom-styles"
        slidesPerView={1.55} >
            <SwiperSlide >
                <Card src="/graphic-card.svg" title="Montagem e manutenção" />
            </SwiperSlide>
            <SwiperSlide >
                <Card src="/printer.svg" title="Manutenção de impressoras" />
            </SwiperSlide>
            <SwiperSlide >
                <Card src="/computer.svg" title="Formatação e instalação de software" />
            </SwiperSlide>
        </Swiper>
        
        
    </div>


 
</div>


