<template>
  <div class="content">
    <div class="md-layout"> 
      <div
        class="md-layout-item md-medium-size-50 md-xsmall-size-100 md-size-25"
      >
        <stats-card data-background-color="green">
          <template slot="header">
            <md-icon>store</md-icon>
          </template>

          <template slot="content">
            <p class="category">사회</p>
            <h3 class="title">13<small>개</small></h3>
          </template>

          <template slot="footer">
            <div class="stats">
              <md-icon>date_range</md-icon>
              최근 2020/10/10
            </div>
          </template>
        </stats-card>
      </div>
      <div
        class="md-layout-item md-medium-size-50 md-xsmall-size-100 md-size-25"
      >
        <stats-card data-background-color="orange">
          <template slot="header">
            <md-icon>content_copy</md-icon>
          </template>

          <template slot="content">
            <p class="category">경제</p>
            <h3 class="title">
              15<small>개</small>
            </h3>
          </template>

          <template slot="footer">
            <div class="stats">
              <md-icon>local_offer</md-icon>
              <a href="#">최근 2020/10/10</a>
            </div>
          </template>
        </stats-card>
      </div>
      <div
        class="md-layout-item md-medium-size-50 md-xsmall-size-100 md-size-25"
      >
        <stats-card data-background-color="red">
          <template slot="header">
            <md-icon>info_outline</md-icon>
          </template>

          <template slot="content">
            <p class="category">정치</p>
            <h3 class="title">75<small>개</small></h3>
          </template>

          <template slot="footer">
            <div class="stats">
              <md-icon>local_offer</md-icon>
              최근 2020/10/10
            </div>
          </template>
        </stats-card>
      </div>
      <div
        class="md-layout-item md-medium-size-50 md-xsmall-size-100 md-size-25"
      >
        <stats-card data-background-color="blue">
          <template slot="header">
            <i class="fab fa-twitter"></i>
          </template>

          <template slot="content">
            <p class="category">과학</p>
            <h3 class="title">45<small>개</small></h3>
          </template>

          <template slot="footer">
            <div class="stats">
              <md-icon>update</md-icon>
              Just Updated
            </div>
          </template>
        </stats-card>
      </div>
      <div
        class="md-layout-item md-medium-size-100 md-xsmall-size-100"
      >
        <nav-tabs-card>
          <template slot="content">
            <span class="md-nav-tabs-title">Category</span>
            <md-tabs class="md-success" md-alignment="left">
              <md-tab id="tab-society" md-label="사회" md-icon="bug_report">
                <nav-tabs-table></nav-tabs-table>
              </md-tab>

              <md-tab id="tab-economy" md-label="경제" md-icon="code">
                <nav-tabs-table></nav-tabs-table>
              </md-tab>

              <md-tab id="tab-politic" md-label="정치" md-icon="cloud">
                <nav-tabs-table></nav-tabs-table>
              </md-tab>

              <md-tab id="tab-science" md-label="과학" md-icon="cloud">
                  <keyword-card data-background-color="green">
                  </keyword-card>
              </md-tab>
            </md-tabs>
          </template>
        </nav-tabs-card>
      </div>
    </div>
  </div>
</template>

<script>
import {
  StatsCard,
  NavTabsCard,
  NavTabsTable,
  KeywordCard,
} from "@/components";

export default {
  components: {
    StatsCard,
    NavTabsCard,
    NavTabsTable,
    KeywordCard,
  },
  data() {
    return {
    };
  }
};
</script>
