<template>
  <div class="wrapper flex-row">
    <cheatsheetNavigation />
    <div class="main-content">
      <h1 class="project" style="margin: 1.5rem 0;">Wilson Language Training Web Style Guide</h1>
      <h2 class="project" id="introduction">Introduction</h2>
      <div class="display-container">
        <h3 class="project">What is a style guide?</h3>
        <p>In the development world, a style guide is a set of standards used for building applications that will establish and enforce consistency across the board.</p>
        <h3 class="project">Why do we need it?</h3>
        <p>With a style guide, we can easily ensure that all Wilson websites and applications are built with the same colors, styles, fonts, etc. which helps us build our brand. Consistency across the board helps customers recognize digital products and makes them look and feel more "authentic."</p>
      </div>

      <h2 class="project" id="colorpalette">Colors Palette &amp; Themes</h2>
      <h4 class="project" id="basiccolors">Basic Colors</h4>
      <div class="display-container">
        <div class="colors">
          <div class="color-block" style="background:#000000; color:#fff">
            <div class="code">$black</div><br>
            #000000<br>
            rgba()
          </div>
          <div class="color-block" style="background:#363636; color:#fff">
            <div class="code">$almost-black</div><br>
            #363636<br>
            rgba()
          </div>
          <div class="color-block" style="background:#5e5e5e; color:#fff">
            <div class="code">$gray--darker</div><br>
            #5e5e5e<br>
            rgba()
          </div>
          <div class="color-block" style="background:#878787; color:#fff">
            <div class="code">$gray--dark</div><br>
            #878787<br>
            rgba()
          </div>
          <div class="color-block" style="background:#c1c1c1; color:#000">
            <div class="code">$gray</div><br>
            #c1c1c1<br>
            rgba()
          </div>
          <div class="color-block" style="background:#e5e5e5; color:#000">
            <div class="code">$gray--light</div><br>
            #e5e5e5<br>
            rgba()
          </div>
          <div class="color-block" style="background:#fbfbfb; color:#000; border: 1px solid #e5e5e5;">
            <div class="code">$almost-white</div><br>
            #fbfbfb<br>
            rgba()
          </div>
          <div class="color-block" style="background:#fff; color:#000; border: 1px solid #e5e5e5;">
            <div class="code">$white</div><br>
            #ffffff<br>
            rgba()
          </div>
        </div>
        
        <div class="colors">
          <div class="color-block" style="background:#cc4d4d; color:#fff;">
            <div class="code">$red</div><br>
            #cc4d4d<br>
            rgba()
          </div>
          <div class="color-block" style="background:#9b4242; color:#fff;">
            <div class="code">$red--dark</div><br>
            #9b4242<br>
            rgba()
          </div>
          <div class="color-block" style="background:#e8b335; color:#fff;">
            <div class="code">$gold</div><br>
            #e8b335<br>
            rgba()
          </div>
          <div class="color-block" style="background:#25b15d; color:#fff;">
            <div class="code">$green</div><br>
            #25b15d<br>
            rgba()
          </div>
          <div class="color-block" style="background:#5a3480; color:#fff;">
            <div class="code">$purple</div><br>
            #5a3480<br>
            rgba()
          </div>
        </div>
      </div>

      <h4 class="project" id="wilsoncolors">Wilson Colors</h4>
      <div class="display-container">
        <div class="colors">
          <div class="primary-block dark" style="background: #003DA5">
            <b>WILSON PRIMARY BLUE</b><br>
            <div class="code">$blue / $wilson-blue</div><br><br>
            #003DA5<br>
            rgba(0,61,165)
          </div>
          <div class="shades">
            <div class="dark" style="background: #001E52">#001E52<br>rgba(0,30,82)</div>
            <div class="dark" style="background: #002E7C">#002E7C<br>rgba(0,46,124)</div>
            <div class="dark" style="background: #406DBB">#406DBB<br>rgba(64,109,187)</div>
            <div class="" style="background: #7F9DD2">#7F9DD2<br>rgba(127,157,210)</div>
            <div class="" style="background: #BFCEE8">#BFCEE8<br>rgba(191,206,232)</div>
          </div>
          <div class="color-vars code">
            <div>$blue--darker</div>
            <div>$blue--dark</div>
            <div>$blue--light</div>
            <div>$blue--lighter</div>
            <div>$blue--lightest</div>
          </div>
        </div>

        <div class="colors">
          <div class="primary-block dark" style="background: #3E84BC">
            <b>WILSON SECONDARY BLUE</b><br>
            <div class="code">$blue2</div><br><br>
            #3E84BC<br>
            rgba(62,132,188)
          </div>
          <div class="shades">
            <div class="dark" style="background: #1F415D">#1F415D<br>rgba(31,65,93)</div>
            <div class="dark" style="background: #2F638D">#2F638D<br>rgba(47,99,141)</div>
            <div class="dark" style="background: #6FA3CD">#6FA3CD<br>rgba(111,163,205)</div>
            <div class="" style="background: #9FC1DD">#9FC1DD<br>rgba(159,193,221)</div>
            <div class="" style="background: #CFE0EE">#CFE0EE<br>rgba(207,224,238)</div>
          </div>
          <div class="color-vars code">
            <div>$blue2--darker</div>
            <div>$blue2--dark</div>
            <div>$blue2--light</div>
            <div>$blue2--lighter</div>
            <div>$blue2--lightest</div>
          </div>
        </div>
      </div>

      <h4 class="project" id="programcommunitycolors">Program/Community Colors</h4>
      <div class="display-container">
        <div class="colors">
          <div class="primary-block" style="background: #8ED8F8">
            <b>FUNDATIONS PRE-K</b><br>
            <div class="code">$pre-k</div><br><br>
            #8ED8F8<br>
            rgba(0,61,165)
          </div>
          <div class="shades">
            <div class="dark" style="background: #466B7B">#466B7B<br>rgba(0,30,82)</div>
            <div class="dark" style="background: #6BA2BA">#6BA2BA<br>rgba(0,46,124)</div>
            <div class="" style="background: #AAE2FA">#AAE2FA<br>rgba(64,109,187)</div>
            <div class="" style="background: #C6EBFB">#C6EBFB<br>rgba(127,157,210)</div>
            <div class="" style="background: #E3F5FD">#E3F5FD<br>rgba(191,206,232)</div>
          </div>
          <div class="color-vars code">
            <div>$pre-k--darker</div>
            <div>$pre-k--dark</div>
            <div>$pre-k--light</div>
            <div>$pre-k--lighter</div>
            <div>$pre-k--lightest</div>
          </div>
        </div>

        <div class="colors">
          <div class="primary-block" style="background: #F1BE48">
            <b>FUNDATIONS / PREVENTION</b><br>
            <div class="code">$fun / $prevention</div><br><br>
            #F1BE48<br>
            rgba(0,61,165)
          </div>
          <div class="shades">
            <div class="dark" style="background: #785E24">#785E24<br>rgba(0,30,82)</div>
            <div class="dark" style="background: #B58F36">#B58F36<br>rgba(0,46,124)</div>
            <div class="" style="background: #F4CE75">#F4CE75<br>rgba(64,109,187)</div>
            <div class="" style="background: #F7DEA2">#F7DEA2<br>rgba(127,157,210)</div>
            <div class="" style="background: #FBEED0">#FBEED0<br>rgba(191,206,232)</div>
          </div>
          <div class="color-vars code">
            <div>$fun--darker / $prevention--darker</div>
            <div>$fun--dark / $prevention--dark</div>
            <div>$fun--light / $prevention--light</div>
            <div>$fun--lighter / $prevention--lighter</div>
            <div>$fun--lightest / $prevention--lightest</div>
          </div>
        </div>

        <div class="colors">
          <div class="primary-block" style="background: #BDD85A">
            <b>FUNDATIONS / EARLY INTERVENTION</b><br>
            <div class="code">$early-intervention</div><br><br>
            #BDD85A<br>
            rgba(0,61,165)
          </div>
          <div class="shades">
            <div class="dark" style="background: #5E6B2D">#5E6B2D<br>rgba(0,30,82)</div>
            <div class="dark" style="background: #8EA244">#8EA244<br>rgba(0,46,124)</div>
            <div class="" style="background: #CDE183">#CDE183<br>rgba(64,109,187)</div>
            <div class="" style="background: #DDEBAB">#DDEBAB<br>rgba(127,157,210)</div>
            <div class="" style="background: #EEF5D5">#EEF5D5<br>rgba(191,206,232)</div>
          </div>
          <div class="color-vars code">
            <div>$early-intervention--darker</div>
            <div>$early-intervention--dark</div>
            <div>$early-intervention--light</div>
            <div>$early-intervention--lighter</div>
            <div>$early-intervention--lightest</div>
          </div>
        </div>

        <div class="colors">
          <div class="primary-block" style="background: #009CDE">
            <b>FUNDATIONS LEVEL K</b><br>
            <div class="code">$funk</div><br><br>
            #009CDE<br>
            rgba(0,61,165)
          </div>
          <div class="shades">
            <div class="dark" style="background: #004D6E">#004D6E<br>rgba(0,30,82)</div>
            <div class="dark" style="background: #0075A7">#0075A7<br>rgba(0,46,124)</div>
            <div class="" style="background: #3FB4E6">#3FB4E6<br>rgba(64,109,187)</div>
            <div class="" style="background: #7ECDEE">#7ECDEE<br>rgba(127,157,210)</div>
            <div class="" style="background: #BEE5F6">#BEE5F6<br>rgba(191,206,232)</div>
          </div>
          <div class="color-vars code">
            <div>$funk--darker</div>
            <div>$funk--dark</div>
            <div>$funk--light</div>
            <div>$funk--lighter</div>
            <div>$funk--lightest</div>
          </div>
        </div>

        <div class="colors">
          <div class="primary-block" style="background: #E8927C">
            <b>FUNDATIONS LEVEL 1</b><br>
            <div class="code">$fun1</div><br><br>
            #E8927C<br>
            rgba(0,61,165)
          </div>
          <div class="shades">
            <div class="dark" style="background: #73483E">#73483E<br>rgba(0,30,82)</div>
            <div class="dark" style="background: #AE6E5D">#AE6E5D<br>rgba(0,46,124)</div>
            <div class="" style="background: #EDAD9C">#EDAD9C<br>rgba(64,109,187)</div>
            <div class="" style="background: #F3C8BC">#F3C8BC<br>rgba(127,157,210)</div>
            <div class="" style="background: #F9E3DD">#F9E3DD<br>rgba(191,206,232)</div>
          </div>
          <div class="color-vars code">
            <div>$fun1--darker</div>
            <div>$fun1--dark</div>
            <div>$fun1--light</div>
            <div>$fun1--lighter</div>
            <div>$fun1--lightest</div>
          </div>
        </div>

        <div class="colors">
          <div class="primary-block" style="background: #5CB8B2">
            <b>FUNDATIONS LEVEL 2</b><br>
            <div class="code">$fun2</div><br><br>
            #5CB8B2<br>
            rgba(0,61,165)
          </div>
          <div class="shades">
            <div class="dark" style="background: #2E5B58">#2E5B58<br>rgba(0,30,82)</div>
            <div class="dark" style="background: #458A86">#458A86<br>rgba(0,46,124)</div>
            <div class="" style="background: #84C9C5">#84C9C5<br>rgba(64,109,187)</div>
            <div class="" style="background: #ACDBD8">#ACDBD8<br>rgba(127,157,210)</div>
            <div class="" style="background: #D5ECEB">#D5ECEB<br>rgba(191,206,232)</div>
          </div>
          <div class="color-vars code">
            <div>$fun2--darker</div>
            <div>$fun2--dark</div>
            <div>$fun2--light</div>
            <div>$fun2--lighter</div>
            <div>$fun2--lightest</div>
          </div>
        </div>

        <div class="colors">
          <div class="primary-block dark" style="background: #9000A5">
            <b>FUNDATIONS LEVEL 3</b><br>
            <div class="code">$fun3</div><br><br>
            #9000A5<br>
            rgba(0,61,165)
          </div>
          <div class="shades">
            <div class="dark" style="background: #480052">#480052<br>rgba(0,30,82)</div>
            <div class="dark" style="background: #6C007C">#6C007C<br>rgba(0,46,124)</div>
            <div class="" style="background: #AC40BC">#AC40BC<br>rgba(64,109,187)</div>
            <div class="" style="background: #C880D2">#C880D2<br>rgba(127,157,210)</div>
            <div class="" style="background: #E3BFE8">#E3BFE8<br>rgba(191,206,232)</div>
          </div>
          <div class="color-vars code">
            <div>$fun3--darker</div>
            <div>$fun3--dark</div>
            <div>$fun3--light</div>
            <div>$fun3--lighter</div>
            <div>$fun3--lightest</div>
          </div>
        </div>

        <div class="colors">
          <div class="primary-block dark" style="background: #5A00A8">
            <b>JUST WORDS / INTERVENTION</b><br>
            <div class="code">$jw / $intervention</div><br><br>
            #5A00A8<br>
            rgba(0,61,165)
          </div>
          <div class="shades">
            <div class="dark" style="background: #2D0054">#2D0054<br>rgba(0,30,82)</div>
            <div class="dark" style="background: #43007E">#43007E<br>rgba(0,46,124)</div>
            <div class="" style="background: #8340BE">#8340BE<br>rgba(64,109,187)</div>
            <div class="" style="background: #AD80D4">#AD80D4<br>rgba(127,157,210)</div>
            <div class="" style="background: #D6BFE9">#D6BFE9<br>rgba(191,206,232)</div>
          </div>
          <div class="color-vars code">
            <div>$jw--darker / $intervention--darker</div>
            <div>$jw--dark / $intervention--dark</div>
            <div>$jw--light / $intervention--light</div>
            <div>$jw--lighter / $intervention--lighter</div>
            <div>$jw--lightest / $intervention--lightest</div>
          </div>
        </div>

        <div class="colors">
          <div class="primary-block dark" style="background: #0047BB">
            <b>WRS / INTENSIVE</b><br>
            <div class="code">$wrs / $intensive</div><br><br>
            #0047BB<br>
            rgba(0,61,165)
          </div>
          <div class="shades">
            <div class="dark" style="background: #00235D">#00235D<br>rgba(0,30,82)</div>
            <div class="dark" style="background: #00358C">#00358C<br>rgba(0,46,124)</div>
            <div class="" style="background: #3F75CC">#3F75CC<br>rgba(64,109,187)</div>
            <div class="" style="background: #7EA2DC">#7EA2DC<br>rgba(127,157,210)</div>
            <div class="" style="background: #BED0ED">#BED0ED<br>rgba(191,206,232)</div>
          </div>
          <div class="color-vars code">
            <div>$wrs--darker / $intensive--darker</div>
            <div>$wrs--dark / $intensive--dark</div>
            <div>$wrs--light / $intensive--light</div>
            <div>$wrs--lighter / $intensive--lighter</div>
            <div>$wrs--lightest / $intensive--lightest</div>
          </div>
        </div>

        <div class="colors">
          <div class="primary-block dark" style="background: #DB7530">
            <b>WILSON PROFESSIONAL COMMUNITY (WPC)</b><br>
            <div class="code">$wpc</div><br><br>
            #DB7530<br>
            rgba(0,61,165)
          </div>
          <div class="shades">
            <div class="dark" style="background: #6D3A18">#6D3A18<br>rgba(0,30,82)</div>
            <div class="dark" style="background: #A45824">#A45824<br>rgba(0,46,124)</div>
            <div class="" style="background: #E49763">#E49763<br>rgba(64,109,187)</div>
            <div class="" style="background: #ECB996">#ECB996<br>rgba(127,157,210)</div>
            <div class="" style="background: #F5DBCA">#F5DBCA<br>rgba(191,206,232)</div>
          </div>
          <div class="color-vars code">
            <div>$wpc--darker</div>
            <div>$wpc--dark</div>
            <div>$wpc--light</div>
            <div>$wpc--lighter</div>
            <div>$wpc--lightest</div>
          </div>
        </div>

        <div class="colors">
          <div class="primary-block dark" style="background: #CB3636">
            <b>ADMINISTRATOR COMMUNITY</b><br>
            <div class="code">$alc</div><br><br>
            #CB3636<br>
            rgba(0,61,165)
          </div>
          <div class="shades">
            <div class="dark" style="background: #651B1B">#651B1B<br>rgba(0,30,82)</div>
            <div class="dark" style="background: #982929">#982929<br>rgba(0,46,124)</div>
            <div class="" style="background: #D86868">#D86868<br>rgba(64,109,187)</div>
            <div class="" style="background: #E49999">#E49999<br>rgba(127,157,210)</div>
            <div class="" style="background: #F1CBCB">#F1CBCB<br>rgba(191,206,232)</div>
          </div>
          <div class="color-vars code">
            <div>$alc--darker</div>
            <div>$alc--dark</div>
            <div>$alc--light</div>
            <div>$alc--lighter</div>
            <div>$alc--lightest</div>
          </div>
        </div>

      </div>

        

      <h2 class="project" id="typography">Typography</h2>
      <h4 class="project" id="basictypography">Basic Typography for General Use</h4>
      <div class="display-container">
        <h1>Heading 1</h1>
        <h2>Heading 2</h2>
        <h3>Heading 3</h3>
        <h4>Heading 4</h4>
        <h5>Heading 5</h5>
        <h6>Heading 6</h6>
        <p>This is a paragraph with a <a href="#">link</a>, some <strong>bold text</strong>, some <em>italicized text</em>, and some <u>underlined text</u>.</p>
      </div>

      <h4 class="project" id="specialtypography">Special Typography for Interactive WebApps and One-Offs (add class="special")</h4>
      <div class="display-container">
        <h1 class="special">Heading 1</h1><code class="code">&lt;h1 class="special"&gt;&lt;/h1&gt;</code>
        <h2 class="special">Heading 2</h2><code class="code">&lt;h2 class="special"&gt;&lt;/h2&gt;</code>
        <h3 class="special">Heading 3</h3><code class="code">&lt;h3 class="special"&gt;&lt;/h3&gt;</code>
        <h4 class="special">Heading 4</h4><code class="code">&lt;h4 class="special"&gt;&lt;/h4&gt;</code>
        <h5 class="special">Heading 5</h5><code class="code">&lt;h5 class="special"&gt;&lt;/h5&gt;</code>
        <p class="special">This is a paragraph with a <a href="#">link</a>, some <strong>bold text</strong>, some <em>italicized text</em>, and some <u>underlined text</u>.</p>
      </div>

      <h2 class="project" id="forms">Forms</h2>
      <div class="display-container">
        <form action="/action_page.php">
          First name:<br>
          <input type="text" name="firstname" placeholder="First name">
          <br>
          Last name:<br>
          <input type="text" name="lastname" placeholder="Last name">
          <br>
          <input type="submit" value="Submit">
        </form> 
      </div>

      <h2 class="project" id="buttons">Buttons</h2>
      <h4 class="project">Custom Wilson Buttons</h4>
        <div class="display-container">
          <button class="lg">Large</button>
          <button class="">Regular</button>
          <button class="sm">Small</button>
          <hr class="lg">
          <button class="primary">Primary</button>
          <button class="secondary">Secondary</button>
          <button class="success">Success</button>
          <button class="warning">Warning</button>
          <button class="unavailable">Unavailable</button>
          <button class="disabled">Disabled</button>
        </div>


      <!-- <h2 class="project" id="modals">Modals</h2>
        <div class="display-container">
          <div class="modal show">
            <header>
              <span>Modal Title</span>
              <span class="close-button"><svg viewbox="0 0 20 20"><path class="close-x" d="M 10,10 L 20,20 M 20,10 L 10,20" /></svg></span>
            </header>
            <div class="modal-content">
              <p><strong>This is just example content:</strong></p>
              <p>More example content here.</p>
            </div>
            <div class="modal-buttons">
              <button class="primary">Okay</button>
              <button class="secondary">Cancel</button>
            </div>
          </div>
        </div> -->
    </div>

  </div>
</template>

<script>
import cheatsheetNavigation from '@/components/cheatsheetNavigation.vue'

export default {
  name: 'cheatsheet',
  components: {
    cheatsheetNavigation
  }
}
</script>

<style lang="scss">
// To Be Moved

// Color Palette
.color-shades {
  display: flex;
  flex-direction: row;
  flex-wrap: nowrap;
  align-items: center;
  margin: 1rem 0.5rem;
  .label {
    font-size: 1rem;
    font-weight: 800;
    letter-spacing: -0.075rem;
    text-transform: uppercase;
    text-align: right;
    width: 15rem;
    margin-right: 1rem;
  }
  .swatch,
  .shade {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    text-align: center;
    color: black;
    width: 3rem;
    height: 5rem;
    &.dark {
      color: white;
    }
    &.primary {
      width: 6rem;
      height: 6rem;
      font-weight: 800;
      font-size: 0.85rem;
    }
    &.border {
      border: 1px solid gray;
      box-sizing: border-box;
    }
  }
  .swatch {
    width: 5rem;
    height: 5rem;
    margin-right: 0.5rem;
    font-weight: 800;
    font-size: 0.85rem;
  }
}
</style>