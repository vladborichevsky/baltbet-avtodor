<template>
  <div class="main_button_wrapper">
  <a class="main_button" href="https://docs.google.com/forms/d/e/1FAIpQLSdQ8gL2cnjC6AxR9UgQUVwX3g9O_DDqY0c0_eWq85AjegTLqA/viewform">
    <span>УЧАСТВОВАТЬ</span>
    <span>
      <svg width="40px" height="43px" viewBox="0 0 66 60" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
        <g id="arrow" stroke="none" stroke-width="1" fill="none" fill-rule="evenodd">
          <path class="one" d="M40.1543933,3.89485454 L43.9763149,0.139296592 C44.1708311,-0.0518420739 44.4826329,-0.0518571125 44.6771675,0.139262789 L65.6916134,20.7848311 C66.0855801,21.1718824 66.0911863,21.8050225 65.704135,22.1989893 C65.7000188,22.2031791 65.6958657,22.2073326 65.6916762,22.2114492 L44.677098,42.8607841 C44.4825957,43.0519059 44.1708242,43.0519358 43.9762853,42.8608513 L40.1545186,39.1069479 C39.9575152,38.9134427 39.9546793,38.5968729 40.1481845,38.3998695 C40.1502893,38.3977268 40.1524132,38.395603 40.1545562,38.3934985 L56.9937789,21.8567812 C57.1908028,21.6632968 57.193672,21.3467273 57.0001876,21.1497035 C56.9980647,21.1475418 56.9959223,21.1453995 56.9937605,21.1432767 L40.1545208,4.60825197 C39.9574869,4.41477773 39.9546013,4.09820839 40.1480756,3.90117456 C40.1501626,3.89904911 40.1522686,3.89694235 40.1543933,3.89485454 Z" fill="#FFFFFF"></path>
          <path class="two" d="M20.1543933,3.89485454 L23.9763149,0.139296592 C24.1708311,-0.0518420739 24.4826329,-0.0518571125 24.6771675,0.139262789 L45.6916134,20.7848311 C46.0855801,21.1718824 46.0911863,21.8050225 45.704135,22.1989893 C45.7000188,22.2031791 45.6958657,22.2073326 45.6916762,22.2114492 L24.677098,42.8607841 C24.4825957,43.0519059 24.1708242,43.0519358 23.9762853,42.8608513 L20.1545186,39.1069479 C19.9575152,38.9134427 19.9546793,38.5968729 20.1481845,38.3998695 C20.1502893,38.3977268 20.1524132,38.395603 20.1545562,38.3934985 L36.9937789,21.8567812 C37.1908028,21.6632968 37.193672,21.3467273 37.0001876,21.1497035 C36.9980647,21.1475418 36.9959223,21.1453995 36.9937605,21.1432767 L20.1545208,4.60825197 C19.9574869,4.41477773 19.9546013,4.09820839 20.1480756,3.90117456 C20.1501626,3.89904911 20.1522686,3.89694235 20.1543933,3.89485454 Z" fill="#FFFFFF"></path>
          <path class="three" d="M0.154393339,3.89485454 L3.97631488,0.139296592 C4.17083111,-0.0518420739 4.48263286,-0.0518571125 4.67716753,0.139262789 L25.6916134,20.7848311 C26.0855801,21.1718824 26.0911863,21.8050225 25.704135,22.1989893 C25.7000188,22.2031791 25.6958657,22.2073326 25.6916762,22.2114492 L4.67709797,42.8607841 C4.48259567,43.0519059 4.17082418,43.0519358 3.97628526,42.8608513 L0.154518591,39.1069479 C-0.0424848215,38.9134427 -0.0453206733,38.5968729 0.148184538,38.3998695 C0.150289256,38.3977268 0.152413239,38.395603 0.154556228,38.3934985 L16.9937789,21.8567812 C17.1908028,21.6632968 17.193672,21.3467273 17.0001876,21.1497035 C16.9980647,21.1475418 16.9959223,21.1453995 16.9937605,21.1432767 L0.15452076,4.60825197 C-0.0425130651,4.41477773 -0.0453986756,4.09820839 0.148075568,3.90117456 C0.150162624,3.89904911 0.152268631,3.89694235 0.154393339,3.89485454 Z" fill="#FFFFFF"></path>
        </g>
      </svg>
    </span> 
  </a>
</div>
</template>


<style lang="scss" scoped>
  @use '@/assets/variables' as vars;

  .main_button_wrapper {
    display: flex;
    justify-content: center;
    align-items: center;
    width: fit-content;
    margin: 20px 0;
  }

  .main_button {
    border-radius: 10px;
    display: flex;
    padding: 10px 45px;
    text-decoration: none;
    font-size: 30px;
    color: white;
    background: vars.$orange-color;
    transition: 1s;
    box-shadow: 10px 10px 0 black;
    transform: skewX(-15deg);
    line-height: 30px;
    font-weight: 700;
  }

  .main_button:focus {
    outline: none; 
  }

  .main_button:hover {
    transition: 0.5s;
    box-shadow: 10px 10px 0 #FBC638;
  }

  .main_button span:nth-child(2) {
    transition: 0.5s;
    margin-right: 0px;
  }

  .main_button:hover  span:nth-child(2) {
    transition: 0.5s;
    margin-right: 45px;
  }

  span {
    height: 32px;
    transform: skewX(15deg);
    line-height: 32px;
  }

  span:nth-child(2) {
    width: 20px;
    margin-left: 30px;
    position: relative;
  }
  
/**************SVG****************/

  path.one {
    transition: 0.5s;
    animation: color_anim 1s infinite 0.6s;
  }

  path.two {
    transition: 0.5s;
    animation: color_anim 1s infinite 0.4s;
  }

  path.three {
    transition: 0.5s;
    animation: color_anim 1s infinite 0.2s;
  }

  .main_button:hover path.three {
    animation: color_anim 1s infinite 0.2s;
  }

  .main_button:hover path.one {
    transform: translateX(0%);
    animation: color_anim 1s infinite 0.6s;
  }

  .main_button:hover path.two {
    transform: translateX(0%);
    animation: color_anim 1s infinite 0.4s;
  }

/* SVG animations */

  @keyframes color_anim {
    0% {
        fill: white;
    }
    50% {
        fill: #FBC638;
    }
    100% {
        fill: white;
    }
  }

  @media (max-width: 992px) {
    .main_button {
      font-size: 25px;
      line-height: 25px;
    }

    .main_button:hover {
      box-shadow: 10px 10px 0 black;
    }

    .main_button:hover  span:nth-child(2) {
      margin-right: 0;
    }
  }

  @media (max-width: 767px) {
    .main_button {
      font-size: 20px;
      line-height: 20px;
      padding: 8px 30px 8px 15px;
    }
  }

  @media (max-width: 576px) {
    .main_button_wrapper {
      margin: 0;
    }

    svg {
      width: 20px;
      height: 23px;
    }

    span {
      height: 20px;
      line-height: 20px;
    }

    span:nth-child(2) {
      width: 20px;
      margin-left: 10px;
    }

    .main_button {
      font-size: 20px;
      line-height: 20px;
      padding: 8px 15px 8px 15px;
    }
  }

  @media (max-width: 440px) {
    .main_button {
      font-size: 16px;
      line-height: 16px;
      padding: 7px 12px 7px 12px;
    }
  }

  @media (max-width: 340px) {
    .main_button {
      font-size: 12px;
      line-height: 12px;
      padding: 5px 10px 5px 10px;
    }
  }
</style>