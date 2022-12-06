<template>
  <q-page>
    <div>
      <q-list>
        <q-item class="gt-sm rt-main-surround" style="height: 140px">
          <q-item-section class="gt-xs col-xs-12 col-sm-6 col-md-4">
          </q-item-section>
          <q-item-section class="col-xs-12 col-sm-6 col-md-4 center">
            <q-item-label
              ><p class="text-h4">{{ $t("title") }}</p></q-item-label
            ></q-item-section
          >
          <q-item-section
            class="col-xs-12 col-sm-6 col-md-4 q-pr-lg"
            style="align-items: end"
          >
            <q-img
              src="~assets/images/qrcode1000.png"
              spinner-color="white"
              style="height: 100px; max-width: 100px"
            />
            <q-item-label
              ><a
                href="https://docs.google.com/forms/d/e/1FAIpQLSfnXX4EmbtrKHE5tLn8QP0DVmVzhJaiJB_ni-KbIm_z59p8yA/viewform"
                target="_blank"
                >校園網路服務支援申請單</a
              >
            </q-item-label>
          </q-item-section>
        </q-item>

        <q-item class="gt-sm" style="height: 375px" id="ems">
          <q-item-section class="col-1"></q-item-section>
          <q-item-section class="col-4 q-mr-lg" style="align-items: end">
            <q-img
              src="~assets/images/kai-wenzel-06MHFfYv6YY-unsplash.jpg"
              spinner-color="white"
              style="height: 280px; max-width: 320px"
            />
          </q-item-section>
          <q-item-section class="col-5">
            <p class="text-h4">
              <a href="https://net.niu.edu.tw/service/ems/" target="_blank"
                >EMS平台</a
              >
            </p>
            <p class="text-subtitle1">
              透過 Google Workspace，提供一組電子郵件信箱及各式各樣的應用服務<br />
              觀看<a href="https://net.niu.edu.tw/service/ems/" target="_blank"
                >使用說明</a
              ><br />
              <a href="https://ems.niu.edu.tw/" target="_blank">使用本服務</a
              ><br />
              若忘記通行碼，校內教職員及在校生可點選線上「忘記密碼」選項，依指示操作自行變更。<em
                >校友請洽校友服務中心辦理</em
              ><br />
              <a
                href="https://net.niu.edu.tw/service/ems_pass_reset_V1.2.pdf"
                target="_blank"
                >EMS密碼重置說明</a
              ><br /><a
                href="https://net.niu.edu.tw/service/ems-pop3.pdf"
                target="_blank"
                >透過Outlook收信設定說明</a
              >
            </p>
          </q-item-section>
          <q-item-section class="col-2"></q-item-section>
        </q-item>

        <q-item
          class="gt-sm rt-main-surround"
          style="height: 375px"
          id="webmail"
        >
          <q-item-section class="col-2"></q-item-section>
          <q-item-section class="col-5 q-mr-lg" style="align-items: end">
            <p class="text-h4">
              <a href="https://mail.niu.edu.tw/" target="_blank"
                >校園Webmail信箱</a
              >
            </p>
            <p class="text-subtitle1" style="text-align: right">
              提供一組郵件帳號，透過Web介面的郵件登入服務<br />
              <em
                >學生信箱僅限在學期間使用，系統會定期刪除畢業學生資訊。為避免信件遺失，請自行備份重要信件</em
              ><br />
              <a href="https://net.niu.edu.tw/service/chpwd.pdf" target="_blank"
                >變更通行碼說明</a
              ><br />
              <a
                href="https://pws.niu.edu.tw/~khtzeng/NUMail.pdf"
                target="_blank"
                >使用手冊</a
              ><br />
              <a href="https://net.niu.edu.tw/e-mail.pdf" target="_blank"
                >申請表下載</a
              >(新帳號申請或忘記通行碼申請重新設定，限教職員使用)<br />
              學生若忘記通行碼，請攜帶學生證，至圖資館一樓資訊網路組辦理<br />
              <a href="https://mail.niu.edu.tw/" target="_blank">使用本服務</a>
            </p>
          </q-item-section>
          <q-item-section class="col-4">
            <q-img
              src="~assets/images/brett-jordan-LPZy4da9aRo-unsplash.jpg"
              spinner-color="white"
              style="height: 280px; max-width: 320px"
            />
          </q-item-section>

          <q-item-section class="col-1"></q-item-section>
        </q-item>

        <q-item class="gt-sm" style="height: 375px" id="wifi">
          <q-item-section class="col-1"></q-item-section>
          <q-item-section class="col-4 q-mr-lg" style="align-items: end">
            <q-img
              src="~assets/images/brett-jordan-OCfHTaB5THQ-unsplash.jpg"
              spinner-color="white"
              style="height: 280px; max-width: 320px"
            />
          </q-item-section>
          <q-item-section class="col-5">
            <p class="text-h4">無線網路</p>
            <p class="text-subtitle1">
              校內透過網頁認證<a
                href="https://net.niu.edu.tw/service/wireless/"
                target="_blank"
                >使用說明</a
              ><br />
              校內透過802.1X認證<a
                href="https://net.niu.edu.tw/service/802.1x/"
                target="_blank"
                >使用說明</a
              ><br />
              臨時無線網路<a
                href="https://net.niu.edu.tw/service/wifi/"
                target="_blank"
                >使用說明</a
              >及<a
                href="https://net.niu.edu.tw/service/wifi.doc"
                target="_blank"
                >申請表</a
              ><br />
              本校師生至其他漫遊學校使用該校無線網路時<br />
              帳號請輸入："mail帳號@niu.edu.tw"<br />
              <a
                href="https://roamingcenter.tanet.edu.tw/select_tanetroaming.php"
                target="_blank"
                >查詢漫遊連線單位</a
              >
            </p>
          </q-item-section>
          <q-item-section class="col-2"></q-item-section>
        </q-item>

        <q-item class="gt-sm rt-main-surround" style="height: 375px" id="vpn">
          <q-item-section class="col-2"></q-item-section>
          <q-item-section class="col-5 q-mr-lg" style="align-items: end">
            <p class="text-h4">SSL VPN連線</p>
            <p class="text-subtitle1" style="text-align: right">
              提供使用者於校外透過本項服務取得本校IP位址，並以此IP位址為識別，使用任何只有在校園網路內才能使用的資源(如電子資料庫)<br />
              Windows作業系統安裝檔下載<br />
              <a
                href="https://net.niu.edu.tw/service/sslvpn/sslvpn_win.pdf"
                target="_blank"
                >操作手冊</a
              ><br />
              <a
                href="https://net.niu.edu.tw/service/sslvpn/PulseSecure.Windows.32-bit.7z"
                target="_blank"
                >32位元版本</a
              ><br />
              <a
                href="https://net.niu.edu.tw/service/sslvpn/PulseSecure.Windows.64-bit.7z"
                target="_blank"
                >64位元版本</a
              ><br />

              <em
                >(若使用Windows 7作業系統，安裝完畢後請勿升級，以免無法使用)</em
              ><br />
              Mac作業系統安裝檔下載<br />
              <a
                href="https://net.niu.edu.tw/service/sslvpn/PulseSecure.MacOS2022.dmg"
                target="_blank"
                >Mac OS2022版本</a
              ><br />
            </p>
          </q-item-section>
          <q-item-section class="col-4">
            <q-img
              src="~assets/images/markus-spiske-L29OcSbFbYo-unsplash.jpg"
              spinner-color="white"
              style="height: 280px; max-width: 320px"
            />
          </q-item-section>

          <q-item-section class="col-1"></q-item-section>
        </q-item>

        <q-item class="gt-sm" style="height: 375px" id="software">
          <q-item-section class="col-1"></q-item-section>
          <q-item-section class="col-4 q-mr-lg" style="align-items: end">
            <q-img
              src="~assets/images/szabo-viktor-qmvl6m4Tots-unsplash.jpg"
              spinner-color="white"
              style="height: 280px; max-width: 320px"
            />
          </q-item-section>
          <q-item-section class="col-5">
            <p class="text-h4">
              <a href="https://software.niu.edu.tw/" target="_blank"
                >軟體下載</a
              >
            </p>
            <p class="text-subtitle1">
              提供校園授權軟體及自由軟體下載 校園授權軟體下載服務僅限校園內 IP
              位址才能使用<br />
              <a href="https://software.niu.edu.tw/" target="_blank"
                >使用本服務</a
              ><br />
              <a href="mailto:abuse@niu.edu.tw">檢舉校內電腦安裝非法軟體</a>
            </p>
          </q-item-section>
          <q-item-section class="col-2"></q-item-section>
        </q-item>

        <q-item
          class="gt-sm rt-main-surround"
          style="height: 375px"
          id="office"
        >
          <q-item-section class="col-2"></q-item-section>
          <q-item-section class="col-5 q-mr-lg" style="align-items: end">
            <p class="text-h4">
              <a href="https://365.niu.edu.tw/" target="_blank"
                >微軟 Office 365</a
              >
            </p>
            <p class="text-subtitle1" style="text-align: right">
              提供在校學生下載安裝使用微軟Office 365軟體<br />
              <a
                href="https://net.niu.edu.tw/service/office365.pdf"
                target="_blank"
                >觀看使用說明</a
              ><br />
              <a href="https://365.niu.edu.tw/" target="_blank">使用本服務</a
              ><br />
              <em
                >若忘記通行碼，可點選線上「忘記密碼」選項，依指示操作自行變更<br />學生亦可攜帶學生證，至圖資館一樓資訊網路組辦理<br
              /></em>
              <a
                href="https://net.niu.edu.tw/service/365_pass_reset.pdf"
                target="_blank"
                >Office 365密碼重置說明</a
              ><br />
            </p>
          </q-item-section>
          <q-item-section class="col-4">
            <q-img
              src="~assets/images/ed-hardie-xG02JzIBf7o-unsplash.jpg"
              spinner-color="white"
              style="height: 280px; max-width: 320px"
            />
          </q-item-section>

          <q-item-section class="col-1"></q-item-section>
        </q-item>
      </q-list>

      <q-list bordered class="rounded-borders lt-md">
        <q-expansion-item
          expand-separator
          :icon="content.icon"
          :label="content.title"
          v-for="(content, index) in mobileContent"
          :key="index"
        >
          <q-card>
            <q-card-section
              v-for="(section, index) in content.contents"
              :key="index"
            >
              <span v-if="section.url == ''" class="text-black">{{
                section.text
              }}</span>
              <q-btn
                v-if="section.url != ''"
                outline
                color="primary"
                :label="section.text"
                @click="openURL(section.url)"
              />
            </q-card-section>
          </q-card>
        </q-expansion-item>
      </q-list>
    </div>

    <!-- place QPageSticky at end of page -->
    <q-page-sticky expand position="top" class="gt-sm" style="opacity: 1">
      <q-toolbar class="bg-accent text-black">
        <q-space />
        <q-toolbar-title
          clickable
          @click="scrollMeTo('ems')"
          style="cursor: pointer"
          shrink
        >
          EMS 平台
        </q-toolbar-title>
        <q-space />
        <q-toolbar-title
          clickable
          @click="scrollMeTo('webmail')"
          style="cursor: pointer"
          shrink
        >
          校園Webmail信箱
        </q-toolbar-title>
        <q-space />
        <q-toolbar-title
          clickable
          @click="scrollMeTo('wifi')"
          style="cursor: pointer"
          shrink
        >
          無線網路
        </q-toolbar-title>
        <q-space />
        <q-toolbar-title
          clickable
          @click="scrollMeTo('vpn')"
          style="cursor: pointer"
          shrink
        >
          SSL VPN連線
        </q-toolbar-title>
        <q-space />
        <q-toolbar-title
          clickable
          @click="scrollMeTo('software')"
          style="cursor: pointer"
          shrink
        >
          軟體下載
        </q-toolbar-title>
        <q-space />
        <q-toolbar-title
          clickable
          @click="scrollMeTo('office')"
          style="cursor: pointer"
          shrink
        >
          微軟 Office 365
        </q-toolbar-title>
        <q-space />
      </q-toolbar>
    </q-page-sticky>

    <q-page-scroller
      position="bottom-right"
      :scroll-offset="150"
      :offset="[18, 18]"
      duration="300"
    >
      <q-btn fab icon="keyboard_arrow_up" color="primary" />
    </q-page-scroller>
  </q-page>
</template>

<script>
const mobileContent = [
  {
    title: "校園網路服務",
    title_url:
      "https://docs.google.com/forms/d/e/1FAIpQLSfnXX4EmbtrKHE5tLn8QP0DVmVzhJaiJB_ni-KbIm_z59p8yA/viewform",
    img: "~assets/images/qrcode1000.png",
    icon: "contact_mail",
    contents: [
      {
        text: "支援申請單",
        url: "https://docs.google.com/forms/d/e/1FAIpQLSfnXX4EmbtrKHE5tLn8QP0DVmVzhJaiJB_ni-KbIm_z59p8yA/viewform",
        style: "",
      },
    ],
  },
  {
    title: "EMS平台",
    title_url: "https://net.niu.edu.tw/service/ems/",
    img: "~assets/images/kai-wenzel-06MHFfYv6YY-unsplash.jpg",
    icon: "cloud_done",
    contents: [
      {
        text: "EMS平台",
        url: "https://net.niu.edu.tw/service/ems/",
        style: "",
      },
      {
        text: "觀看使用說明",
        url: "https://net.niu.edu.tw/service/ems/",
        style: "",
      },
      {
        text: "使用本服務",
        url: "https://ems.niu.edu.tw/",
        style: "",
      },
      {
        text: "EMS密碼重置說明",
        url: "https://net.niu.edu.tw/service/ems_pass_reset_V1.2.pdf",
        style: "",
      },
      {
        text: "透過Outlook收信設定說明",
        url: "https://net.niu.edu.tw/service/ems-pop3.pdf",
        style: "",
      },
    ],
  },
  {
    title: "校園Webmail信箱",
    title_url: "https://mail.niu.edu.tw/",
    img: "~assets/images/brett-jordan-LPZy4da9aRo-unsplash.jpg",
    icon: "email",
    contents: [
      {
        text: "校園Webmail信箱",
        url: "https://mail.niu.edu.tw/",
        style: "",
      },
      {
        text: "學生信箱僅限在學期間使用，系統會定期刪除畢業學生資訊。請自行備份重要信件",
        url: "",
        style: "em",
      },
      {
        text: "變更通行碼說明",
        url: "https://net.niu.edu.tw/service/chpwd.pdf",
        style: "",
      },
      {
        text: "使用手冊",
        url: "https://pws.niu.edu.tw/~khtzeng/NUMail.pdf",
        style: "",
      },
      {
        text: "申請表下載",
        url: "https://net.niu.edu.tw/e-mail.pdf",
        style: "",
      },
      {
        text: "忘記密碼，請攜帶學生證，至圖資館一樓網路組辦理",
        url: "",
        style: "",
      },
      {
        text: "使用本服務",
        url: "https://mail.niu.edu.tw/",
        style: "",
      },
    ],
  },
  {
    title: "無線網路",
    title_url: "",
    img: "~assets/images/brett-jordan-OCfHTaB5THQ-unsplash.jpg",
    icon: "network_check",
    contents: [
      {
        text: "校內透過網頁認證使用說明",
        url: "https://net.niu.edu.tw/service/wireless/",
        style: "",
      },
      {
        text: "校內透過802.1X認證使用說明",
        url: "https://net.niu.edu.tw/service/802.1x/",
        style: "",
      },
      {
        text: "臨時無線網路使用說明",
        url: "https://net.niu.edu.tw/service/wifi/",
        style: "",
      },
      {
        text: "臨時無線網路申請表",
        url: "https://net.niu.edu.tw/service/wifi.doc",
        style: "",
      },
      {
        text: '本校師生至其他漫遊學校使用該校無線網路時， 帳號請輸入："mail帳號@niu.edu.tw"',
        url: "",
        style: "",
      },
      {
        text: "查詢漫遊連線單位",
        url: "https://roamingcenter.tanet.edu.tw/select_tanetroaming.php",
        style: "",
      },
    ],
  },
  {
    title: "SSL VPN連線",
    title_url: "",
    img: "~assets/images/markus-spiske-L29OcSbFbYo-unsplash.jpg",
    icon: "vpn_lock",
    contents: [
      {
        text: "SSL VPN連線操作手冊",
        url: "https://net.niu.edu.tw/service/sslvpn/sslvpn_win.pdf",
        style: "",
      },
      {
        text: "32位元版本",
        url: "https://net.niu.edu.tw/service/sslvpn/PulseSecure.Windows.32-bit.7z",
        style: "",
      },
      {
        text: "64位元版本",
        url: "https://net.niu.edu.tw/service/sslvpn/PulseSecure.Windows.64-bit.7z",
        style: "",
      },
      {
        text: "若使用Windows 7作業系統，安裝完畢後請勿升級，以免無法使用",
        url: "",
        style: "em",
      },
      {
        text: '本校師生至其他漫遊學校使用該校無線網路時，帳號請輸入："mail帳號@niu.edu.tw"',
        url: "",
        style: "",
      },
      {
        text: "Mac作業系統安裝檔下載",
        url: "https://net.niu.edu.tw/service/sslvpn/PulseSecure.MacOS2022.dmg",
        style: "",
      },
    ],
  },
  {
    title: "軟體下載",
    title_url: "https://software.niu.edu.tw/",
    img: "~assets/images/szabo-viktor-qmvl6m4Tots-unsplash.jpg",
    icon: "file_download",
    contents: [
      {
        text: "下載服務僅限校園內 IP",
        url: "",
        style: "",
      },
      {
        text: "使用本服務",
        url: "https://software.niu.edu.tw/",
        style: "",
      },
      {
        text: "檢舉校內電腦安裝非法軟體",
        url: "mailto:abuse@niu.edu.tw",
        style: "",
      },
    ],
  },
  {
    title: "微軟 Office 365",
    title_url: "https://365.niu.edu.tw/",
    img: "~assets/images/ed-hardie-xG02JzIBf7o-unsplash.jpg",
    icon: "event_note",
    contents: [
      {
        text: "使用本服務",
        url: "https://365.niu.edu.tw/",
        style: "",
      },
      {
        text: "觀看使用說明",
        url: "https://net.niu.edu.tw/service/office365.pdf",
        style: "",
      },

      {
        text: "Office 365密碼重置說明",
        url: "https://net.niu.edu.tw/service/365_pass_reset.pdf",
        style: "",
      },
    ],
  },
];

import { defineComponent, ref } from "vue";
import { openURL } from "quasar";
import { useI18n } from "vue-i18n";

export default defineComponent({
  name: "IndexPage",

  setup() {
    function scrollMeTo(refName) {
      var element = document.getElementById(refName);

      element.scrollIntoView({ behavior: "smooth" });
    }

    return {
      scrollMeTo,
      mobileContent,
      openURL,
    };
  },
});
</script>
