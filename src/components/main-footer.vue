<template>
  <div class="main-footer">
    <div class="footer-logo">
      <img src="src/assets/logo.svg" />
    </div>
    <footer>
      <div class="footer-info">
        <svg
          xmlns="http://www.w3.org/2000/svg"
          width="24"
          height="24"
          viewBox="0 0 24 24"
        >
          <g
            id="Group_34"
            data-name="Group 34"
            transform="translate(0)"
          >
            <rect
              id="Rectangle_11_Copy_2"
              data-name="Rectangle 11 Copy 2"
              width="24"
              height="24"
              fill="none"
            />
            <g id="place" transform="translate(0 3)">
              <path
                id="Shape"
                d="M6.188,18h0A41.608,41.608,0,0,1,3.094,13.9C1.682,11.77,0,8.718,0,6.3A6.326,6.326,0,0,1,1.8,1.834a6.163,6.163,0,0,1,8.773,0,6.326,6.326,0,0,1,1.8,4.466c0,2.418-1.682,5.47-3.094,7.6A41.608,41.608,0,0,1,6.188,18Zm0-13.95A2.206,2.206,0,0,0,3.978,6.3,2.21,2.21,0,1,0,8.4,6.3,2.206,2.206,0,0,0,6.188,4.05Z"
                fill="#fff"
              />
            </g>
          </g>
        </svg>
        <div class="description">
          <p>
            Lorem ipsum dolor sit amet, consectetur
            adipiscing elit, sed do eiusmod tempor
            incididunt ut labore et dolore magna aliqua
          </p>
        </div>
      </div>

      <div class="contact-info">
        <div class="phone">
          <svg
            id="Group_21"
            data-name="Group 21"
            xmlns="http://www.w3.org/2000/svg"
            width="24"
            height="24"
            viewBox="0 0 24 24"
          >
            <rect
              id="Rectangle_11_Copy"
              data-name="Rectangle 11 Copy"
              width="24"
              height="24"
              fill="none"
            />
            <g
              id="phone-in-talk"
              transform="translate(3 3)"
            >
              <path
                id="Shape"
                d="M17,18A16.892,16.892,0,0,1,4.975,13.025,16.892,16.892,0,0,1,0,1,.947.947,0,0,1,1,0H4.5a.947.947,0,0,1,1,1A13.336,13.336,0,0,0,6,4.5a.8.8,0,0,1-.2,1L3.6,7.7a15.572,15.572,0,0,0,6.6,6.6l2.2-2.2a1.4,1.4,0,0,1,.741-.239.818.818,0,0,1,.259.039,11.361,11.361,0,0,0,3.6.6.947.947,0,0,1,1,1V17A.947.947,0,0,1,17,18Zm1-9H16A6.926,6.926,0,0,0,9,2V0a8.962,8.962,0,0,1,9,9ZM14,9H12A2.934,2.934,0,0,0,9,6V4a4.947,4.947,0,0,1,5,5Z"
                fill="#fff"
              />
            </g>
          </svg>

          <p>+1-543-123-4567</p>
        </div>
        <div class="email">
          <svg
            id="Group_12"
            data-name="Group 12"
            xmlns="http://www.w3.org/2000/svg"
            width="24"
            height="24"
            viewBox="0 0 24 24"
          >
            <rect
              id="Rectangle_11"
              data-name="Rectangle 11"
              width="24"
              height="24"
              fill="none"
            />
            <path
              id="Shape"
              d="M18,16H2a2,2,0,0,1-2-2V2A2,2,0,0,1,2,0H18a2,2,0,0,1,2,2V14A2,2,0,0,1,18,16ZM16,5.2V14h2V2H16.8L10,6.2,3.2,2H2V14H4V5.2L10,9l6-3.8Z"
              transform="translate(2 4)"
              fill="#fff"
            />
          </svg>
          <p>example.fylo.com</p>
        </div>
      </div>
      <nav>
        <ul class="first-nav">
          <li><a>About Us</a></li>
          <li><a>Jobs</a></li>
          <li><a>Press</a></li>
          <li><a>Blog</a></li>
        </ul>
        <ul class="second-nav">
          <li><a>Contact Us</a></li>
          <li><a>Terms</a></li>
          <li><a>Privacy</a></li>
        </ul>
      </nav>
      <div class="social"></div>
    </footer>
  </div>
</template>

<script>
export default {
  name: 'main-footer',
}
</script>
