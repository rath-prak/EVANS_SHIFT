<template>
  <div class="shift-education-page">
    <main class="page">
      <!-- Top bar with logo -->
      <header class="topbar" aria-label="Medivet Animal Health">
        <a href="https://www.medivet.com.kh/" target="_blank" rel="noopener noreferrer">
          <img
            src="./images/Medivet-logo-primary.svg"
            width="221"
            height="49"
            alt="Medivet Animal Health"
            loading="eager"
          />
        </a>
        <p class="topbar__text">MEDIVET ANIMAL HEALTH</p>
      </header>

      <!-- CTA ribbon -->
      <section class="ribbon" aria-label="Product info sheet">
        <div class="ribbon__box">
          <span>SHIFT™</span>
          <img src="./images/Icons/evans_house.svg" alt="" class="ribbon__icon" />
        </div>
      </section>

      <!-- Main Section: Fundamentals of Farm Biosecurity -->
      <section class="education-intro">
        <h1 class="education-intro__title" lang="km">មូលដ្ឋានគ្រឹះនៃសុវត្ថិភាពកសិដ្ឋាន</h1>
        <p class="education-intro__paragraph" lang="km">ការរក្សាការពារជីវៈសុវត្ថិភាព និងអនាម័យដែលមានប្រសិទ្ធភាពខ្លាំងគឺជាកត្តាសំខាន់បំផុតក្នុងការការពារសុខភាពសត្វ ការការពារការផ្ទុះជំងឺ និងការធានាសុវត្ថិភាពកសិដ្ឋាន។ ការសម្អាត និងសម្លាប់មេរោគដែលមានគុណភាពខ្ពស់ជួយកាត់បន្ថយការរីករាលដាលនៃបាក់តេរី វីរុស ផ្សិត និងមេរោគផ្សេងៗទៀតដែលតែងតែរកឃើញនៅក្នុងរោងសត្វ ឧបករណ៍ និងប្រព័ន្ធទឹក។</p>
        <h2 class="education-intro__subtitle" lang="km">គោលការណ៍ទាំង ៣ នៃកម្មវិធីជីវៈសុវត្ថិភាពមានប្រសិទ្ធភាព</h2>
      </section>

      <!-- Blue Flow Bar with Downward Arrow -->
      <section class="flow-bar">
        <div class="flow-bar__container">
          <span class="flow-bar__step" lang="km">សម្អាត</span>
          <span class="flow-bar__arrow">→</span>
          <span class="flow-bar__step" lang="km">សម្លាប់មេរោគ</span>
          <span class="flow-bar__arrow">→</span>
          <span class="flow-bar__step" lang="km">អនាម័យទឹក</span>
          <span class="flow-bar__arrow-down">↓</span>
        </div>
      </section>

      <!-- Three Step Cards -->
      <section class="principles-steps">
        <!-- Step 1: Clean -->
        <div class="principle-card">
          <div class="principle-card__icon">
            <span class="principle-card__badge">1</span>
            <div class="principle-card__illustration">
              <!-- Illustration placeholder - spray cleaning surface -->
              <img src="./images/Icons/evans_spray.svg" alt="" class="principle-card__icon-img" />
            </div>
          </div>
          <h3 class="principle-card__title" lang="km">១. សម្អាត៖ កម្ចាត់របាំងការពារ</h3>
          <p class="principle-card__text" lang="km">ភាពកខ្វក់ លាមក និងខ្លាញ់ដើរតួជារបាំងការពារសម្រាប់មេរោគប្រឆាំងនឹងទឹកថ្នាំសម្លាប់មេរោគ។ គោលការណ៍គឺត្រូវសម្អាតរបាំងសរីរាង្គទាំងនេះជាមុនសិន ពីព្រោះការសម្អាតដែលមានប្រសិទ្ធភាពបង្ហាញមេរោគ ធ្វើឱ្យពួកវាមានភាពងាយរងគ្រោះ។</p>
        </div>
        <div class="principle-card__arrow-down">↓</div>

        <!-- Step 2: Disinfect -->
        <div class="principle-card">
          <div class="principle-card__icon">
            <span class="principle-card__badge">2</span>
            <div class="principle-card__illustration">
              <img src="./images/Icons/evans_disinfect.svg" alt="" class="principle-card__icon-img" />
            </div>
          </div>
          <h3 class="principle-card__title" lang="km">២. សម្លាប់មេរោគ៖ កម្ចាត់ការគំរាមកំហែង</h3>
          <p class="principle-card__text" lang="km">សូម្បីតែផ្ទៃដែលមើលទៅស្អាតក៏អាចមានមេរោគរាប់លានដែលមើលមិនឃើញ និងគ្រោះថ្នាក់។ គោលការណ៍គឺត្រូវកម្ចាត់មេរោគទាំងស្រុងនៅពេលដែលសារធាតុសរីរាង្គត្រូវបានយកចេញ ដោយប្រើទឹកថ្នាំសម្លាប់មេរោគដែលមានវិសាលភាពទូលំទូលាយដើម្បីបំបែកខ្សែសង្វាក់នៃការឆ្លងជំងឺ និងធានាសុវត្ថិភាពកសិដ្ឋានមុនពេលសត្វថ្មីមកដល់។</p>
        </div>
        <div class="principle-card__arrow-down">↓</div>

        <!-- Step 3: Water Hygiene -->
        <div class="principle-card">
          <div class="principle-card__icon">
            <span class="principle-card__badge">3</span>
            <div class="principle-card__illustration">
              <img src="./images/Icons/water.svg" alt="" class="principle-card__icon-img" />
            </div>
          </div>
          <h3 class="principle-card__title" lang="km">៣. អនាម័យទឹក៖ សម្អាតភ្នាក់ងារចម្លង</h3>
          <p class="principle-card__text" lang="km">បំពង់ទឹកគឺជាប្រភពនៃការបំពុលដែលត្រូវបានភ្លេច។ ខ្សែភាពយន្ត (ស្រទាប់រអិល) កើតឡើងនៅក្នុងបំពង់ ផ្ទុកបាក់តេរី និងរីករាលដាលមេរោគទៅកាន់សត្វស្អាតជារៀងរាល់ថ្ងៃ។ គោលការណ៍គឺថាជីវៈសុវត្ថិភាពក៏គ្របដណ្តប់លើផ្នែកខាងក្នុងនៃបំពង់ទឹកផងដែរ ដែលត្រូវការការរំលាយខ្សែភាពយន្តដើម្បីធានាថាប្រព័ន្ធទឹកផ្តល់ទឹកស្អាត មិនមែនមេរោគ។</p>
        </div>
      </section>

      <!-- Second Section: Farm Sanitation Process -->
      <section class="education-process">
        <h1 class="education-process__title" lang="km">ដំណើរការអនាម័យក្នុងកសិដ្ឋាន</h1>
        
        <!-- Small Flow Line -->
        <div class="flow-bar flow-bar--small">
          <div class="flow-bar__container">
            <span class="flow-bar__step" lang="km">សម្អាត</span>
            <span class="flow-bar__arrow">→</span>
            <span class="flow-bar__step" lang="km">សម្លាប់មេរោគ</span>
            <span class="flow-bar__arrow">→</span>
            <span class="flow-bar__step" lang="km">អនាម័យទឹក</span>
            <span class="flow-bar__arrow-down">↓</span>
          </div>
        </div>
      </section>

      <!-- Product Panels -->
      <section class="product-panels">
        <!-- Panel 1: Cleaning (Purple) -->
        <div class="product-panel product-panel--purple">
          <div class="product-panel__header">
            <span class="product-panel__number">1</span>
            <h3 class="product-panel__title" lang="km">ការសម្អាត (កម្ចាត់សារធាតុសរីរាង្គ)</h3>
          </div>
          
          <div class="product-panel__content">
            <div class="product-panel__illustration">
              <img src="./images/Icons/evans_spray.svg" alt="" class="product-panel__illustration-img" />
            </div>
            
            <div class="product-panel__text">
              <h4 class="product-panel__why" lang="km">ហេតុអ្វីរាសំខាន់</h4>
              <p class="product-panel__description" lang="km">ការសម្អាតយកលាមក ធូលី និងកាកសំណល់សរីរាង្គដែលរារាំងប្រសិទ្ធភាពនៃទឹកថ្នាំសម្លាប់មេរោគ និងកែលម្អប្រសិទ្ធភាពនៃម៉ាស៊ីនបាញ់ទឹក។ វាជាការចាំបាច់មុនពេលប្រើប្រាស់ទឹកថ្នាំសម្លាប់មេរោគ។</p>
              
              <ul class="product-panel__bullets">
                <li lang="km">កម្ចាត់ភាពកខ្វក់ កម្រាល និងកាកសំណល់ចំណី</li>
                <li lang="km">គឺជាការចាំបាច់ មុនពេលប្រើប្រាស់ទឹកថ្នាំសម្លាប់មេរោគ</li>
              </ul>
              
              <div class="product-panel__product-label">
                <strong lang="km">ផលិតផល:</strong> <span lang="km">SHIFT™</span>
              </div>
              
              <div class="product-panel__result">
                <strong lang="km">លទ្ធផល:</strong>
                <p lang="km">ផ្ទៃត្រូវបានសម្អាត និងត្រៀមរួចរាល់សម្រាប់ការសម្លាប់មេរោគដែលមានប្រសិទ្ធភាព។</p>
              </div>
            </div>
            
            <div class="product-panel__image">
              <img src="./images/evans_shift.png" alt="SHIFT" class="product-panel__product-img" />
            </div>
          </div>
          
          <div class="product-panel__footer"></div>
          <div class="product-panel__arrow-down">↓</div>
        </div>

        <!-- Panel 2: Disinfection (Red) -->
        <div class="product-panel product-panel--red">
          <div class="product-panel__header">
            <span class="product-panel__number">2</span>
            <h3 class="product-panel__title" lang="km">ការសម្លាប់មេរោគ</h3>
          </div>
          
          <div class="product-panel__content">
            <div class="product-panel__illustration">
              <img src="./images/Icons/evans_disinfect.svg" alt="" class="product-panel__illustration-img" />
            </div>
            
            <div class="product-panel__text">
              <h4 class="product-panel__why" lang="km">ហេតុអ្វីរាសំខាន់</h4>
              <p class="product-panel__description" lang="km">ការសម្លាប់មេរោគកាត់បន្ថយបាក់តេរី វីរុស និងផ្សិតដែលគ្រោះថ្នាក់ សូម្បីតែនៅក្នុងវត្តមាននៃសារធាតុសរីរាង្គ ដូច្នេះការការពារការផ្ទុះជំងឺ។</p>
              
              <ul class="product-panel__bullets">
                <li lang="km">ប្រើប្រាស់នៅតាមរោងចិញ្ចឹមមាន់ ជ្រូក និងគោ</li>
                <li lang="km">ប្រើលើកម្រាល ជញ្ជាំង ឧបករណ៍ និងអាងសម្លាប់មេជ្រលក់ជើង</li>
              </ul>
              
              <div class="product-panel__product-label">
                <strong lang="km">ផលិតផល:</strong>
                <span lang="km">FAM® 30 (សម្រាប់អាងជ្រលក់ជើង & ឧបករណ៍)</span>
                <span lang="km">GPC8™ (សម្រាប់រោង & កម្រាល)</span>
              </div>
              
              <div class="product-panel__result">
                <strong lang="km">លទ្ធផល:</strong>
                <p lang="km">កម្ចាត់ជំងឺថយចុះ និងជីវៈសុវត្ថិភាពក្នុងកសិដ្ឋានកាន់តែរឹងមាំ។</p>
              </div>
            </div>
            
            <div class="product-panel__image product-panel__image--multiple">
              <img src="./images/evans_shift.png" alt="FAM 30" class="product-panel__product-img" />
              <img src="./images/evans_shift.png" alt="GPC8" class="product-panel__product-img" />
            </div>
          </div>
          
          <div class="product-panel__footer"></div>
          <div class="product-panel__arrow-down">↓</div>
        </div>

        <!-- Panel 3: Water System Hygiene (Red) -->
        <div class="product-panel product-panel--red">
          <div class="product-panel__header">
            <span class="product-panel__number">3</span>
            <h3 class="product-panel__title" lang="km">អនាម័យប្រព័ន្ធទឹក</h3>
          </div>
          
          <div class="product-panel__content">
            <div class="product-panel__illustration">
              <img src="./images/Icons/water.svg" alt="" class="product-panel__illustration-img" />
            </div>
            
            <div class="product-panel__text">
              <h4 class="product-panel__why" lang="km">ហេតុអ្វីរាសំខាន់</h4>
              <p class="product-panel__description" lang="km">បំពង់ទឹកអាចបង្កើតខ្សែភាពយន្ត និងមេរោគ ដែលបំពុលសត្វម្តងទៀត និងកាត់បន្ថយប្រសិទ្ធភាពវ៉ាក់សាំង។ ការយកខ្សែភាពយន្តចេញកែលម្អគុណភាពទឹក។</p>
              
              <ul class="product-panel__bullets">
                <li lang="km">សម្អាតធុងទឹក បំពង់មេ បំពង់ និងក្បាលទឹក</li>
                <li lang="km">កម្ចាត់មេរោគដែលលាក់ខ្លួន និងភាពរអិល</li>
              </ul>
              
              <div class="product-panel__product-label">
                <strong lang="km">ផលិតផល:</strong> <span lang="km">PERADOX™</span>
              </div>
              
              <div class="product-panel__result">
                <strong lang="km">លទ្ធផល:</strong>
                <p lang="km">ប្រព័ន្ធទឹកស្អាតជាងមុន និងការផឹកទឹករបស់សត្វមានសុវត្ថិភាពជាងមុន។</p>
              </div>
            </div>
            
            <div class="product-panel__image">
              <img src="./images/evans_shift.png" alt="PERADOX" class="product-panel__product-img" />
            </div>
          </div>
          
          <div class="product-panel__footer"></div>
        </div>
      </section>

      <!-- Concluding Statement -->
      <section class="education-conclusion">
        <p class="education-conclusion__text" lang="km">កម្មវិធីអនាម័យដែលផ្តោតលើការការពារជាចម្បង ជួយពង្រឹងសុខភាពសត្វ និងបង្កើនផលិតភាពកសិដ្ឋាន នៅគ្រប់ប្រព័ន្ធផលិតកម្ម។</p>
      </section>

      <!-- Footer blue panel -->
      <footer class="shift-footer">
        <h2 class="shift-footer__title">QUALITY & ENVIRONMENTAL ASSURANCE</h2>
        <p class="shift-footer__text">All products in this range are manufactured in the UK by Evans Vanodine International PLC. They operate under ISO 9001 (Quality Management) and ISO 14001 (Environmental Management) international standards, ensuring the highest level of quality, safety, and environmental protection for the agricultural sector.</p>
        <p class="shift-footer__distributor">Imported and Distributed by Medivet Cambodia</p>
      </footer>
    </main>
  </div>
</template>

<script setup>
definePageMeta({
  layout: false,
});

useHead({
  title: 'SHIFT™ Educational — Medivet Animal Health',
  meta: [
    { name: 'description', content: 'Farm Safety and Biosecurity Education' },
    { property: 'og:title', content: 'SHIFT™ Educational — Medivet Animal Health' },
    { property: 'og:description', content: 'Farm Safety and Biosecurity Education' },
    { name: 'theme-color', content: '#745771' }
  ],
  link: [
    { rel: 'preconnect', href: 'https://fonts.googleapis.com' },
    { rel: 'preconnect', href: 'https://fonts.gstatic.com', crossorigin: '' },
    { 
      href: 'https://fonts.googleapis.com/css2?family=Koulen&family=Kantumruy+Pro:wght@400;500;600;700&family=Manrope:wght@400;600;700&display=swap',
      rel: 'stylesheet'
    }
  ]
})
</script>

<style scoped>
.shift-education-page {
  background: var(--bg);
}

/* Education Intro Section */
.education-intro {
  margin: var(--space-6) 0;
  text-align: center;
}

.education-intro__title {
  font-family: "Kantumruy Pro", system-ui, -apple-system, Segoe UI, Roboto, Arial, sans-serif;
  font-size: clamp(20px, 5.5vw, 24px);
  font-weight: 700;
  color: #133588;
  margin: 0 0 var(--space-4);
  line-height: 1.4;
}

.education-intro__paragraph {
  font-family: "Kantumruy Pro", system-ui, -apple-system, Segoe UI, Roboto, Arial, sans-serif;
  font-size: clamp(13px, 3.5vw, 15px);
  font-weight: 500;
  color: var(--font-color);
  line-height: 1.6;
  margin: 0 0 var(--space-5);
  text-align: left;
}

.education-intro__subtitle {
  font-family: "Kantumruy Pro", system-ui, -apple-system, Segoe UI, Roboto, Arial, sans-serif;
  font-size: clamp(18px, 5vw, 22px);
  font-weight: 700;
  color: #133588;
  margin: var(--space-6) 0 var(--space-4);
  text-align: center;
}

/* Flow Bar */
.flow-bar {
  margin: var(--space-6) 0;
  background: var(--blue-box);
  border-radius: 3px;
  padding: var(--space-4) var(--space-3);
}

.flow-bar--small {
  background: transparent;
  padding: var(--space-3) 0;
}

.flow-bar__container {
  display: flex;
  align-items: center;
  justify-content: center;
  gap: var(--space-2);
  flex-wrap: wrap;
}

.flow-bar__step {
  font-family: "Kantumruy Pro", system-ui, -apple-system, Segoe UI, Roboto, Arial, sans-serif;
  font-size: clamp(14px, 3.8vw, 16px);
  font-weight: 700;
  color: #ffffff;
  background: rgba(255, 255, 255, 0.2);
  padding: var(--space-2) var(--space-3);
  border-radius: 3px;
}

.flow-bar--small .flow-bar__step {
  background: #e8f0fe;
  color: var(--blue-box);
}

.flow-bar__arrow {
  font-size: clamp(16px, 4.5vw, 20px);
  color: #ffffff;
  font-weight: 700;
  line-height: 1;
}

.flow-bar--small .flow-bar__arrow {
  color: var(--blue-box);
}

.flow-bar__arrow-down {
  font-size: clamp(24px, 6.5vw, 32px);
  color: #ffffff;
  font-weight: 700;
  line-height: 1;
  margin-left: var(--space-2);
}

.flow-bar--small .flow-bar__arrow-down {
  color: var(--blue-box);
}

/* Principles Steps */
.principles-steps {
  margin: var(--space-6) 0;
}

.principle-card {
  background: #ffffff;
  border-radius: 3px;
  padding: var(--space-5);
  margin-bottom: var(--space-4);
  box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
}

.principle-card__icon {
  width: 100px;
  height: 100px;
  border-radius: 50%;
  background: #e8f0fe;
  display: flex;
  align-items: center;
  justify-content: center;
  margin: 0 auto var(--space-4);
  position: relative;
}

.principle-card__badge {
  position: absolute;
  top: 8px;
  left: 8px;
  font-family: "Manrope", system-ui, -apple-system, Segoe UI, Roboto, Arial, sans-serif;
  font-size: 24px;
  font-weight: 800;
  color: #ffffff;
  background: var(--blue-box);
  width: 32px;
  height: 32px;
  border-radius: 50%;
  display: flex;
  align-items: center;
  justify-content: center;
}

.principle-card__illustration {
  width: 60px;
  height: 60px;
  display: flex;
  align-items: center;
  justify-content: center;
}

.principle-card__icon-img {
  width: 100%;
  height: 100%;
  object-fit: contain;
}

.principle-card__title {
  font-family: "Kantumruy Pro", system-ui, -apple-system, Segoe UI, Roboto, Arial, sans-serif;
  font-size: clamp(16px, 4.5vw, 20px);
  font-weight: 700;
  color: #133588;
  margin: 0 0 var(--space-3);
  text-align: center;
}

.principle-card__text {
  font-family: "Kantumruy Pro", system-ui, -apple-system, Segoe UI, Roboto, Arial, sans-serif;
  font-size: clamp(13px, 3.5vw, 15px);
  font-weight: 500;
  color: var(--font-color);
  line-height: 1.6;
  margin: 0;
  text-align: left;
}

.principle-card__arrow-down {
  text-align: center;
  font-size: clamp(28px, 7.5vw, 36px);
  color: var(--blue-box);
  font-weight: 700;
  line-height: 1;
  margin: var(--space-4) 0;
}

/* Education Process Section */
.education-process {
  margin: var(--space-8) 0 var(--space-6);
}

.education-process__title {
  font-family: "Kantumruy Pro", system-ui, -apple-system, Segoe UI, Roboto, Arial, sans-serif;
  font-size: clamp(20px, 5.5vw, 24px);
  font-weight: 700;
  color: #133588;
  margin: 0 0 var(--space-4);
  text-align: center;
}

/* Product Panels */
.product-panels {
  margin: var(--space-6) 0;
}

.product-panel {
  background: #ffffff;
  border-radius: 3px;
  margin-bottom: var(--space-6);
  overflow: hidden;
  box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
  position: relative;
}

.product-panel__header {
  display: flex;
  align-items: center;
  gap: var(--space-3);
  padding: var(--space-4) var(--space-5);
}

.product-panel--purple .product-panel__header {
  background: linear-gradient(to right, #745771, #594256);
}

.product-panel--red .product-panel__header {
  background: #dc2626;
}

.product-panel__number {
  font-family: "Manrope", system-ui, -apple-system, Segoe UI, Roboto, Arial, sans-serif;
  font-size: 28px;
  font-weight: 800;
  color: #ffffff;
  background: rgba(255, 255, 255, 0.2);
  width: 48px;
  height: 48px;
  border-radius: 3px;
  display: flex;
  align-items: center;
  justify-content: center;
  flex-shrink: 0;
}

.product-panel__title {
  font-family: "Kantumruy Pro", system-ui, -apple-system, Segoe UI, Roboto, Arial, sans-serif;
  font-size: clamp(16px, 4.5vw, 20px);
  font-weight: 700;
  color: #ffffff;
  margin: 0;
  flex: 1;
}

.product-panel__content {
  display: grid;
  grid-template-columns: 80px 1fr auto;
  gap: var(--space-4);
  padding: var(--space-5);
  align-items: start;
}

.product-panel__illustration {
  display: flex;
  align-items: center;
  justify-content: center;
}

.product-panel__illustration-img {
  width: 60px;
  height: 60px;
  object-fit: contain;
}

.product-panel__text {
  min-width: 0;
}

.product-panel__why {
  font-family: "Kantumruy Pro", system-ui, -apple-system, Segoe UI, Roboto, Arial, sans-serif;
  font-size: clamp(14px, 3.8vw, 16px);
  font-weight: 700;
  color: #133588;
  margin: 0 0 var(--space-2);
}

.product-panel__description {
  font-family: "Kantumruy Pro", system-ui, -apple-system, Segoe UI, Roboto, Arial, sans-serif;
  font-size: clamp(12px, 3.2vw, 14px);
  font-weight: 500;
  color: var(--font-color);
  line-height: 1.6;
  margin: 0 0 var(--space-3);
}

.product-panel__bullets {
  list-style: none;
  padding: 0;
  margin: 0 0 var(--space-3);
}

.product-panel__bullets li {
  font-family: "Kantumruy Pro", system-ui, -apple-system, Segoe UI, Roboto, Arial, sans-serif;
  font-size: clamp(12px, 3.2vw, 14px);
  font-weight: 500;
  color: var(--font-color);
  line-height: 1.6;
  margin-bottom: var(--space-2);
  padding-left: var(--space-4);
  position: relative;
}

.product-panel__bullets li::before {
  content: "•";
  position: absolute;
  left: 0;
  color: var(--font-color);
}

.product-panel__product-label {
  font-family: "Kantumruy Pro", system-ui, -apple-system, Segoe UI, Roboto, Arial, sans-serif;
  font-size: clamp(12px, 3.2vw, 14px);
  font-weight: 600;
  color: var(--font-color);
  margin-bottom: var(--space-3);
  display: flex;
  flex-direction: column;
  gap: var(--space-1);
}

.product-panel__product-label strong {
  font-weight: 700;
}

.product-panel__result {
  font-family: "Kantumruy Pro", system-ui, -apple-system, Segoe UI, Roboto, Arial, sans-serif;
  font-size: clamp(12px, 3.2vw, 14px);
  font-weight: 500;
  color: var(--font-color);
}

.product-panel__result strong {
  font-weight: 700;
  display: block;
  margin-bottom: var(--space-1);
}

.product-panel__result p {
  margin: 0;
  line-height: 1.6;
}

.product-panel__image {
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: var(--space-3);
  min-width: 100px;
}

.product-panel__image--multiple {
  gap: var(--space-2);
}

.product-panel__product-img {
  width: 80px;
  height: auto;
  max-height: 120px;
  object-fit: contain;
}

.product-panel__footer {
  height: 4px;
  width: 100%;
}

.product-panel--purple .product-panel__footer {
  background: linear-gradient(to right, #745771, #594256);
}

.product-panel--red .product-panel__footer {
  background: #dc2626;
}

.product-panel__arrow-down {
  text-align: right;
  font-size: clamp(28px, 7.5vw, 36px);
  color: var(--blue-box);
  font-weight: 700;
  line-height: 1;
  margin: var(--space-3) var(--space-5) var(--space-4);
  padding-right: var(--space-2);
}

/* Education Conclusion */
.education-conclusion {
  margin: var(--space-8) 0 var(--space-6);
  padding: var(--space-5);
  background: rgba(116, 87, 113, 0.1);
  border-radius: 3px;
}

.education-conclusion__text {
  font-family: "Kantumruy Pro", system-ui, -apple-system, Segoe UI, Roboto, Arial, sans-serif;
  font-size: clamp(14px, 3.8vw, 16px);
  font-weight: 600;
  color: var(--font-color);
  line-height: 1.6;
  margin: 0;
  text-align: center;
}
</style>
