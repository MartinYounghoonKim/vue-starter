<template>
  <div :class="$style.components">
    <vue-grid>

      <vue-grid-item fill>
        <div class="h1">Tab</div>
      </vue-grid-item>

      <vue-grid-item fill>
        <vue-tab-group>
          <vue-tab-item title="Profile" icon="fas fa-user">
            Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut
            labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores
            et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet.
            Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut
            labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores
            et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet.
          </vue-tab-item>
          <vue-tab-item title="Settings" icon="fas fa-cog">
            et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet.
            Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut
            labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores
            et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet.
          </vue-tab-item>
          <vue-tab-item title="Upload" icon="fas fa-upload">
            Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut
            labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores
            et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet.
          </vue-tab-item>
        </vue-tab-group>
      </vue-grid-item>

    </vue-grid>

    <vue-grid>

      <vue-grid-item fill>
        <div class="h1">Collapse</div>
      </vue-grid-item>

      <vue-grid-item fill>
        <vue-button @click="collapseDemo = !collapseDemo" accent>Collapse toggle</vue-button>
        <vue-collapse :show="collapseDemo">
          <div :class="$style.collapseDemo">
            Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut
            labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores
            et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet.
            Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut
            labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores
            et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet.
          </div>
        </vue-collapse>
      </vue-grid-item>

    </vue-grid>

    <vue-grid>
      <vue-grid-item fill>
        <h1>{{ $t('App.nav.components' /*Components*/) }}</h1>
      </vue-grid-item>

      <vue-grid-item fill>
        <div class="h1">Buttons</div>
      </vue-grid-item>

      <vue-grid-item fill>
        <vue-button>Default</vue-button>
        <vue-button disabled>Default</vue-button>
        <!--<vue-button loading>Loading</vue-button>-->
        <vue-button pulse>Pulse</vue-button>
      </vue-grid-item>

      <vue-grid-item fill>
        <vue-button primary>Primary</vue-button>
        <vue-button primary disabled>Primary</vue-button>
        <!--<vue-button primary loading>Loading</vue-button>-->
        <vue-button primary pulse>Pulse</vue-button>
      </vue-grid-item>

      <vue-grid-item fill>
        <vue-button accent>Accent</vue-button>
        <vue-button accent disabled>Accent</vue-button>
        <!--<vue-button accent loading>Loading</vue-button>-->
        <vue-button accent pulse>Pulse</vue-button>
      </vue-grid-item>

      <vue-grid-item fill>
        <vue-button warn>Warn</vue-button>
        <vue-button warn disabled>Warn</vue-button>
        <!--<vue-button warn loading>Loading</vue-button>-->
        <vue-button warn pulse>Pulse</vue-button>
      </vue-grid-item>

    </vue-grid>

    <vue-grid>

      <vue-grid-item fill>
        <div class="h1">Loader</div>
      </vue-grid-item>

      <vue-grid-item fill>
        <vue-loader />
        <!--<vue-loader medium />-->
        <!--<vue-loader large />-->
        <!--<vue-loader large primary />-->
        <!--<vue-loader large accent />-->
        <!--<vue-loader large warn />-->
      </vue-grid-item>

    </vue-grid>

    <vue-grid>

      <vue-grid-item fill>
        <div class="h1">Headlines</div>
      </vue-grid-item>

      <vue-grid-item fill>
        <h1>Headline 1</h1>
        <h2>Headline 2</h2>
        <h3>Headline 3</h3>
        <h4>Headline 4</h4>
        <h5>Headline 5</h5>
        <h6>Headline 6</h6>
      </vue-grid-item>

    </vue-grid>

    <vue-grid>

      <vue-grid-item fill>
        <div class="h1">Panels</div>
      </vue-grid-item>

      <vue-panel>
        <vue-panel-header title="Title" subtitle="subtitle"
          image="https://avatars2.githubusercontent.com/u/1667598?s=460&v=4" />
        <vue-panel-body>
          Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut
          labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores
          et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet.
          Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut
          labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores
          et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet.
        </vue-panel-body>
        <vue-panel-footer>
          <vue-button warn>Delete</vue-button>
          <vue-button>Cancel</vue-button>
        </vue-panel-footer>
      </vue-panel>

      <vue-panel>
        <vue-panel-header title="Title" subtitle="subtitle" />
        <vue-panel-body>
          Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut
          labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores
          et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet.
          Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut
          labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores
          et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet.
        </vue-panel-body>
        <vue-panel-footer>
          <vue-button warn>Delete</vue-button>
          <vue-button>Cancel</vue-button>
        </vue-panel-footer>
      </vue-panel>

      <vue-panel>
        <vue-panel-header title="Title" subtitle="subtitle"
          image="https://avatars2.githubusercontent.com/u/1667598?s=460&v=4" />
        <vue-panel-body>
          Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut
          labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores
          et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet.
          Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut
          labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores
          et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet.
        </vue-panel-body>
        <vue-panel-footer>
          <vue-button warn>Delete</vue-button>
          <vue-button>Cancel</vue-button>
        </vue-panel-footer>
      </vue-panel>

      <vue-panel>
        <vue-panel-header title="Title" subtitle="subtitle" />
        <vue-panel-body>
          Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut
          labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores
          et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet.
          Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut
          labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores
          et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet.
        </vue-panel-body>
        <vue-panel-footer>
          <vue-button warn>Delete</vue-button>
          <vue-button>Cancel</vue-button>
        </vue-panel-footer>
      </vue-panel>

      <vue-panel>
        <vue-panel-header title="Title" subtitle="subtitle"
          image="https://avatars2.githubusercontent.com/u/1667598?s=460&v=4" />
        <vue-panel-body>
          Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut
          labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores
          et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet.
          Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut
          labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores
          et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet.
        </vue-panel-body>
        <vue-panel-footer>
          <vue-button warn>Delete</vue-button>
          <vue-button>Cancel</vue-button>
        </vue-panel-footer>
      </vue-panel>

      <vue-panel>
        <vue-panel-header title="Title" subtitle="subtitle" />
        <vue-panel-body>
          Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut
          labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores
          et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet.
          Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut
          labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores
          et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet.
        </vue-panel-body>
        <vue-panel-footer>
          <vue-button warn>Delete</vue-button>
          <vue-button>Cancel</vue-button>
        </vue-panel-footer>
      </vue-panel>

    </vue-grid>

    <vue-grid>

      <vue-grid-item fill>
        <div class="h1">Inputs</div>
      </vue-grid-item>

      <vue-grid-item>
        <vue-input placeholder="Placeholder" message="test" />
      </vue-grid-item>

      <vue-grid-item>
        <vue-input placeholder="Placeholder" disabled value="test" />
      </vue-grid-item>

    </vue-grid>

    <vue-grid>

      <vue-grid-item fill>
        <div class="h1">Modal</div>
      </vue-grid-item>

      <vue-grid-item>
        <vue-button primary @click="showModal = !showModal">Show Modal</vue-button>
        <vue-modal :show="showModal" @close="showModal = !showModal">
          <vue-button warn @click="showModal = !showModal">X</vue-button>
          TEST
        </vue-modal>
      </vue-grid-item>

    </vue-grid>
  </div>
</template>

<script lang="ts">
  import VueGrid from '../../shared/components/VueGrid/VueGrid';
  import VueGridItem from '../../shared/components/VueGridItem/VueGridItem';
  import VueButton from '../../shared/components/VueButton/VueButton';
  import VueLoader from '../../shared/components/VueLoader/VueLoader';
  import VuePanel from '../../shared/components/VuePanel/VuePanel';
  import VuePanelHeader from '../../shared/components/VuePanel/VuePanelHeader/VuePanelHeader';
  import VuePanelBody from '../../shared/components/VuePanel/VuePanelBody/VuePanelBody';
  import VuePanelFooter from '../../shared/components/VuePanel/VuePanelFooter/VuePanelFooter';
  import VueInput from '../../shared/components/VueInput/VueInput';
  import VueCollapse from '../../shared/components/VueCollapse/VueCollapse';
  import VueModal from '../../shared/components/VueModal/VueModal';
  import VueTabGroup from '../../shared/components/VueTabGroup/VueTabGroup';
  import VueTabItem from '../../shared/components/VueTabItem/VueTabItem';

  export default {
    metaInfo: {
      title: 'Components'
    },
    components: {
      VueGrid,
      VueGridItem,
      VueButton,
      VueLoader,
      VuePanel,
      VuePanelHeader,
      VuePanelBody,
      VuePanelFooter,
      VueInput,
      VueCollapse,
      VueModal,
      VueTabGroup,
      VueTabItem,
    },
    data() {
      return {
        collapseDemo: true,
        showModal: false,
      }
    }
  };
</script>

<style lang="scss" module>
  @import "../../shared/variables";

  .components {
    margin-top: $nav-bar-height;
  }

  :global {
    .h1 {
      border-bottom: 1px solid $divider-color;
      margin:        $grid-unit * 4 0 $grid-unit * 4 0;
      font-size:     $font-size-h1;
    }
  }

  .collapseDemo {
    padding:    $grid-unit * 2;
    background: $panel-bg;
    box-shadow: $panel-shadow;
    color:      #FFF
  }
</style>
