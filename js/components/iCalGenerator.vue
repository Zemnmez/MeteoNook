<template>
    <b-form class='border rounded p-3'>
        <h2>{{ $t('oAddToCalendar') }}</h2>
        <p>{{ $t('oAddToCalendarDesc') }}</p>

        <b-form-group
            :label="$t('oAddtoCalendarWeatherEvents')"
            label-class='pt-0'
            label-cols-sm='4'>

        </b-form-group>
    </b-form>
</template>

<script lang="ts">
import { Vue, Component, Prop } from 'vue-property-decorator'
import ForecastConfig from './ForecastConfig.vue';

@Component({ components: { ForecastConfig }})
export default class ICalGenerator extends Vue {


}
</script>