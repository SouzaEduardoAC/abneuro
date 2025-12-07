<script setup lang="ts">
import { useHead } from '@unhead/vue' // Supondo uso de Unhead ou Nuxt para meta tags

// Configuração de Meta Tags para SEO
useHead({
  title: 'Dra. Ana Caroline Benin | Neurologista e Clínica Médica em Blumenau',
  meta: [
    {
      name: 'description',
      content: 'Neurologia e Medicina Interna com visão integral. Tratamento de enxaqueca, dores de cabeça, AVC, neuromodulação, fibromialgia, demência, reabilitação, memória na MesoClinic, Blumenau. Agende sua consulta.'
    },
    { name: 'robots', content: 'index, follow' }
  ],
  script: [
    {
      type: 'application/ld+json',
      innerHTML: JSON.stringify({
        "@context": "https://schema.org",
        "@type": "Physician",
        "name": "Dra. Ana Caroline Benin",
        "description": "Especialista em Neurologia e Medicina Interna com visão integral da saúde.",
        "address": {
          "@type": "PostalAddress",
          "streetAddress": "R. Cel. Vidal Ramos, 405, Jardim Blumenau",
          "addressLocality": "Blumenau",
          "addressRegion": "SC",
          "addressCountry": "BR"
        },
        "telephone": "+5547996987678",
        "medicalSpecialty": ["Neurology", "Internal Medicine"],
        "url": "https://anabenin.com.br"
      })
    }
  ]
})
</script>