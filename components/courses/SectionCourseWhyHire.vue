<template>
<!-- This example requires Tailwind CSS v2.0+ -->
  <section
  class="container max-w-screen-2xl mx-auto py-8"
  id="why-hire">
    <div class="bg-white lg:m-12">
      <div class="max-w-7xl mx-auto">
        <div class="lg:text-center">
          <h2 class="text-center mb-8 text-4xl lg:text-5xl font-bold lg:mx-24">
            {{ $t('online_courses.why_hire.headline') }}
          </h2>
          <p class="text-center text-gray-500 text-xl lg:mx-32 font-normal mb-12">
            {{ $t('online_courses.why_hire.sub_headline') }}
          </p>
        </div>

        <div class="mt-10">
          <dl class="space-y-10 md:space-y-0 md:grid md:grid-cols-2 md:gap-x-8 md:gap-y-10">
            <div class="relative">
              <dt>
                <div class="absolute flex items-center justify-center h-12 w-12 rounded-md bg-indigo-500 text-white">
                  <!-- Heroicon name: outline/globe-alt -->
                  <svg
                    class="h-6 w-6"
                    xmlns="http://www.w3.org/2000/svg"
                    fill="currentColor"
                    viewBox="0 0 512 512"
                    stroke="currentColor"
                    aria-hidden="true">
                      <path
                        d="M296,452c-5.52,0-10,4.48-10,10c0,5.52,4.48,10,10,10c5.52,0,10-4.48,10-10C306,456.48,301.52,452,296,452z"/>
                      <path
                        d="M436,46h-30V30c0-16.542-13.458-30-30-30H136c-16.542,0-30,13.458-30,30v16H76c-16.542,0-30,13.458-30,30
          c0,65.057,30.442,112.867,79.828,126.178c16.93,37.265,43.698,68.944,77.674,91.835c7.826,5.273,12.498,14.3,12.498,24.147v55.099
          c-6.855,1.758-13.144,5.322-18.281,10.46C190.162,391.277,186,401.32,186,412h-10c-16.542,0-30,13.458-30,30v60
          c0,5.523,4.478,10,10,10h200c5.522,0,10-4.477,10-10v-60c0-16.542-13.458-30-30-30h-10c0-18.604-12.767-34.283-30-38.734V318.21
          c0-9.879,4.675-18.923,12.508-24.196c33.979-22.893,60.747-54.573,77.676-91.839C435.563,188.859,466,141.052,466,76
          C466,59.458,452.542,46,436,46z M66,76c0-5.514,4.486-10,10-10h30v44.7c0,22.795,3.453,45.117,10.27,66.614
          C84.447,161.551,66,125.146,66,76z M336,432c5.514,0,10,4.486,10,10v50H166v-50c0-5.514,4.486-10,10-10H336z M386,110.7
          c0,27.316-5.438,53.896-16.166,79c-15.26,35.717-40.33,66.052-72.498,87.725C283.976,286.418,276,301.665,276,318.21V382
          c0,5.523,4.478,10,10,10c11.028,0,20,8.972,20,20H206c0-5.338,2.082-10.359,5.861-14.139c3.594-3.594,8.311-5.652,13.355-5.846
          c0.259,0.02,0.52,0.03,0.783,0.03c5.522,0,10-4.522,10-10.045v-63.84c0-16.51-7.971-31.737-21.322-40.733
          c-32.171-21.674-57.241-52.009-72.503-87.729C131.442,164.603,126,138.024,126,110.7V30c0-5.514,4.486-10,10-10h240
          c5.514,0,10,4.486,10,10V110.7z M395.734,177.312C402.548,155.81,406,133.489,406,110.7V66h30c5.514,0,10,4.486,10,10
          C446,125.143,427.555,161.547,395.734,177.312z"/>
                      <path
                        d="M335.139,118.16c-1.175-3.621-4.305-6.26-8.073-6.806l-43.156-6.264l-19.303-39.115c-1.685-3.414-5.161-5.575-8.968-5.575
          c-3.807,0-7.283,2.161-8.968,5.575l-19.303,39.115l-43.155,6.264c-3.768,0.547-6.897,3.186-8.074,6.806
          c-1.176,3.621-0.195,7.595,2.531,10.252l31.234,30.44l-7.372,42.987c-0.643,3.752,0.899,7.543,3.979,9.781
          c3.08,2.237,7.163,2.532,10.531,0.761l38.598-20.293l38.607,20.293c3.39,1.782,7.471,1.462,10.531-0.762
          c3.079-2.238,4.621-6.03,3.977-9.782l-7.38-42.986l31.233-30.439C335.335,125.755,336.315,121.781,335.139,118.16z
           M283.65,148.198c-2.357,2.298-3.434,5.609-2.876,8.854l4.841,28.197l-25.323-13.311c-2.915-1.531-6.395-1.531-9.306,0.001
          l-25.315,13.31l4.836-28.199c0.556-3.245-0.52-6.555-2.877-8.852l-20.484-19.964l28.301-4.108
          c3.258-0.473,6.074-2.519,7.531-5.471l12.662-25.659l12.662,25.659c1.457,2.952,4.273,4.998,7.531,5.471l28.302,4.108
          L283.65,148.198z"/>
                      <path
                        d="M256,452h-40c-5.522,0-10,4.477-10,10s4.478,10,10,10h40c5.522,0,10-4.477,10-10S261.522,452,256,452z"/>
                      <path d="M410.01,482h5.575C412.745,481.437,410.835,481.381,410.01,482z"/>
                  </svg>
                </div>
                <p class="ml-16 mb-4 text-2xl font-semibold text-gray-900">
                  {{ $t('online_courses.why_hire.feature_1_header') }}</p>
              </dt>
              <dd class="mt-2 ml-16 text-lg text-gray-500 font-normal">
                {{ $t('online_courses.why_hire.feature_1_description') }}
              </dd>
            </div>

            <div class="relative">
              <dt>
                <div class="absolute flex items-center justify-center h-12 w-12 rounded-md bg-indigo-500 text-white">
                  <!-- Heroicon name: outline/scale -->
                  <svg
                    class="h-6 w-6"
                    xmlns="http://www.w3.org/2000/svg"
                    fill="currentColor"
                    viewBox="0 0 455.344 455.344"
                    stroke="currentColor"
                    aria-hidden="true">
                      <path
                        d="M453.672,399.672l-100.8-134.4c-3.2-4-9.6-4-12.8,0l-28,37.6l-25.6,34.4l-110.4-148v-27.2h94.4c3.2,0,6.4-2.4,7.2-4.8
          c0.8-3.2,0-6.4-2.4-8.8l-40.8-37.6l40.8-37.6c2.4-2.4,3.2-5.6,2.4-8.8c-1.6-2.4-4-4.8-8-4.8h-93.6v-8.8c0-4.8-3.2-8-8-8
          s-8,3.2-8,8v16.8v86.4v35.2l-158.4,210.4c-1.6,2.4-2.4,5.6-0.8,8c1.6,2.4,4,4.8,7.2,4.8h319.2h120c3.2,0,5.6-1.6,7.2-4.8
          C456.072,404.472,455.272,402.072,453.672,399.672z M176.072,75.672h73.6l-32,29.6c-1.6,1.6-2.4,4-2.4,5.6c0,1.6,0.8,4.8,2.4,5.6
          l32,29.6h-73.6V75.672z M346.472,283.672l21.6,29.6l-6.4,12l-5.6-8.8c-1.6-2.4-4-3.2-6.4-3.2c-2.4,0-4.8,0.8-6.4,3.2l-6.4,7.2
          l-8-16L346.472,283.672z M168.072,205.272l38.4,51.2l-17.6,28.8l-14.4-20.8c-1.6-2.4-4-3.2-6.4-3.2c-2.4,0-4.8,0.8-6.4,3.2
          l-13.6,16.8l-15.2-29.6L168.072,205.272z M24.072,396.472l97.6-130.4l16.8,33.6c1.6,2.4,4,4,6.4,4c2.4,0,5.6-0.8,7.2-3.2
          l14.4-18.4l15.2,22.4c1.6,2.4,4,3.2,6.4,3.2c2.4,0,4.8-1.6,6.4-4l20.8-33.6l94.4,126.4H24.072z M331.272,395.672v0.8l-34.4-46.4
          l21.6-28.8l11.2,19.2c1.6,2.4,4,4,6.4,4c2.4,0,4.8-0.8,7.2-3.2l6.4-8l7.2,10.4c1.6,2.4,4,3.2,6.4,3.2c0,0,0,0,0.8,0
          c2.4,0,5.6-1.6,6.4-4l8.8-16.8l52,69.6H331.272z"/>
                  </svg>
                </div>
                <p class="ml-16 mb-4 text-2xl font-semibold text-gray-900">
                  {{ $t('online_courses.why_hire.feature_2_header') }}</p>
              </dt>
              <dd class="mt-2 ml-16 text-lg text-gray-500 font-normal">
                {{ $t('online_courses.why_hire.feature_2_description') }}
              </dd>
            </div>

            <div class="relative">
              <dt>
                <div class="absolute flex items-center justify-center h-12 w-12 rounded-md bg-indigo-500 text-white">
                  <!-- Heroicon name: outline/lightning-bolt -->
                  <svg
                    class="h-6 w-6"
                    xmlns="http://www.w3.org/2000/svg"
                    fill="currentColor"
                    viewBox="0 0 24 24"
                    stroke="currentColor"
                    aria-hidden="true">
                      <path d="M17 10.5V7c0-.55-.45-1-1-1H4c-.55 0-1 .45-1 1v10c0 .55.45 1 1 1h12c.55 0 1-.45 1-1v-3.5l4 4v-11l-4 4zM14 13h-3v3H9v-3H6v-2h3V8h2v3h3v2z"/>
                  </svg>
                </div>
                <p class="ml-16 mb-4 text-2xl font-bold text-gray-900">{{ $t('online_courses.why_hire.feature_3_header') }}</p>
              </dt>
              <dd class="mt-2 ml-16 text-lg text-gray-500 font-normal">
                {{ $t('online_courses.why_hire.feature_3_description') }}
              </dd>
            </div>

            <div class="relative">
              <dt>
                <div class="absolute flex items-center justify-center h-12 w-12 rounded-md bg-indigo-500 text-white">
                  <!-- Heroicon name: outline/annotation -->
                  <svg
                    class="h-6 w-6"
                    xmlns="http://www.w3.org/2000/svg"
                    fill="currentColor"
                    viewBox="0 -47 512.00002 512"
                    stroke="currentColor"
                    aria-hidden="true">
                      <path
                        d="m507.105469 95.203125-161.90625-61.726563c-3.925781-1.496093-8.320313.472657-9.816407 4.394532-1.496093 3.925781.472657 8.320312 4.398438 9.816406l143.269531 54.621094-99.179687 37.816406-124.734375-56.476562c-3.828125-1.734376-8.332031-.035157-10.0625 3.789062-1.734375 3.828125-.035157 8.332031 3.789062 10.066406l110.988281 50.253906-107.851562 41.117188-227.050781-86.566406 227.050781-86.566406 55.953125 21.335937c3.917969 1.492187 8.316406-.472656 9.816406-4.398437 1.496094-3.921876-.472656-8.316407-4.398437-9.8125l-58.660156-22.367188c-1.746094-.664062-3.675782-.667969-5.421876 0l-248.394531 94.703125c-2.945312 1.125-4.894531 3.953125-4.894531 7.105469v34.726562c0 3.152344 1.949219 5.980469 4.894531 7.105469l77.566407 29.570313v26.351562c0 4.199219 3.402343 7.605469 7.601562 7.605469 4.203125 0 7.605469-3.40625 7.605469-7.605469v-20.550781l155.621093 59.332031c.875.332031 1.792969.5 2.710938.5s1.835938-.167969 2.710938-.5l117.304687-44.722656v120.34375c-36.828125 19.332031-78.125 29.691406-120.015625 29.691406-57.171875 0-113.25-19.273438-158.332031-54.347656v-59.328125c0-4.199219-3.402344-7.605469-7.605469-7.605469-4.199219 0-7.601562 3.40625-7.601562 7.605469v63.011719c0 2.308593 1.046874 4.492187 2.847656 5.933593 48.246094 38.652344 108.867187 59.9375 170.691406 59.9375 41.695312 0 82.835938-9.695312 120.015625-27.855469v30.777344c-12.253906 3.347656-21.289063 14.570313-21.289063 27.871094 0 15.929688 12.960938 28.894531 28.890626 28.894531 15.933593 0 28.894531-12.964843 28.894531-28.894531 0-13.300781-9.035157-24.523438-21.289063-27.871094v-38.808594c12.394532-7.050781 24.269532-15.074218 35.472656-24.050781 1.800782-1.441406 2.851563-3.625 2.851563-5.933593v-119.785157l77.558594-29.570312c2.945312-1.121094 4.894531-3.949219 4.894531-7.105469v-34.722656c0-3.152344-1.949219-5.980469-4.894531-7.105469zm-109.800781 294.953125c0 7.542969-6.140626 13.683594-13.6875 13.683594-7.542969 0-13.683594-6.140625-13.683594-13.683594 0-7.546875 6.140625-13.6875 13.683594-13.6875 7.546874 0 13.6875 6.140625 13.6875 13.6875zm-382.097657-276.808594 233.1875 88.90625v18.445313l-233.1875-88.90625zm248.398438 107.351563v-18.445313l112.410156-42.859375v18.449219zm150.730469 69.105469c-7.417969 5.773437-15.140626 11.109374-23.113282 16.007812v-117.492188l23.113282-8.8125zm-23.113282-117.761719v-18.445313l105.570313-40.25v18.445313zm0 0"/>
                  </svg>
                </div>
                <p class="ml-16 mb-4 text-2xl font-semibold text-gray-900">
                  {{ $t('online_courses.why_hire.feature_4_header') }}</p>
              </dt>
              <dd class="mt-2 ml-16 text-lg text-gray-500 font-normal">
                {{ $t('online_courses.why_hire.feature_4_description') }}
              </dd>
            </div>
          </dl>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'SectionCourseWhyHire'
}
</script>
