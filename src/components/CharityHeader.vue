<template>
  <div class="head">
    <div class="middle-row">
      <div class="charity">
        <img src="../assets/charity-logo.png" alt="charity-image" />
      </div>
      <div class="contact">
        <div class="sub-contact flex">
          <div id="contact-styling" class="email">
            <div class="logo">
              <svg
                xmlns="http://www.w3.org/2000/svg"
                width="24"
                height="24"
                viewBox="0 0 24 24"
              >
                <path
                  fill="#f14b05"
                  d="m16.484 11.976l6.151-5.344v10.627zm-7.926.905l2.16 1.875c.339.288.781.462 1.264.462h.017h-.001h.014c.484 0 .926-.175 1.269-.465l-.003.002l2.16-1.875l6.566 5.639H1.995zM1.986 5.365h20.03l-9.621 8.356a.612.612 0 0 1-.38.132h-.014h.001h-.014a.61.61 0 0 1-.381-.133l.001.001zm-.621 1.266l6.15 5.344l-6.15 5.28zm21.6-2.441c-.24-.12-.522-.19-.821-.19H1.859a1.87 1.87 0 0 0-.835.197l.011-.005A1.856 1.856 0 0 0 0 5.855v12.172a1.86 1.86 0 0 0 1.858 1.858h20.283a1.86 1.86 0 0 0 1.858-1.858V5.855c0-.727-.419-1.357-1.029-1.66l-.011-.005z"
                />
              </svg>
            </div>
            <div class="writeup">
              <h4>EMAIL</h4>
              <p>companyname@mail.com</p>
            </div>
          </div>
          <div id="contact-styling" class="call">
            <div class="logo">
              <svg
                xmlns="http://www.w3.org/2000/svg"
                width="24"
                height="24"
                viewBox="0 0 24 24"
              >
                <g fill="none">
                  <path
                    d="M24 0v24H0V0h24ZM12.593 23.258l-.011.002l-.071.035l-.02.004l-.014-.004l-.071-.035c-.01-.004-.019-.001-.024.005l-.004.01l-.017.428l.005.02l.01.013l.104.074l.015.004l.012-.004l.104-.074l.012-.016l.004-.017l-.017-.427c-.002-.01-.009-.017-.017-.018Zm.265-.113l-.013.002l-.185.093l-.01.01l-.003.011l.018.43l.005.012l.008.007l.201.093c.012.004.023 0 .029-.008l.004-.014l-.034-.614c-.003-.012-.01-.02-.02-.022Zm-.715.002a.023.023 0 0 0-.027.006l-.006.014l-.034.614c0 .012.007.02.017.024l.015-.002l.201-.093l.01-.008l.004-.011l.017-.43l-.003-.012l-.01-.01l-.184-.092Z"
                  />
                  <path
                    fill="#f14b05"
                    d="M6.857 2.445C8 3.278 8.89 4.415 9.65 5.503l.442.644l.417.615a1.504 1.504 0 0 1-.256 1.986l-1.951 1.449a.48.48 0 0 0-.142.616c.442.803 1.228 1.999 2.128 2.899c.901.9 2.153 1.738 3.012 2.23a.483.483 0 0 0 .644-.162l1.27-1.933a1.503 1.503 0 0 1 2.056-.332l.663.459c1.239.86 2.57 1.837 3.588 3.14a1.47 1.47 0 0 1 .189 1.484c-.837 1.953-2.955 3.616-5.158 3.535l-.3-.017l-.233-.02l-.258-.03l-.281-.038l-.305-.05a11.66 11.66 0 0 1-.16-.03l-.336-.072a12.399 12.399 0 0 1-.176-.04l-.366-.094l-.385-.11l-.402-.13c-1.846-.626-4.189-1.856-6.593-4.26c-2.403-2.403-3.633-4.746-4.259-6.592l-.13-.402l-.11-.385l-.094-.366l-.078-.346a11.79 11.79 0 0 1-.063-.326l-.05-.305l-.04-.281l-.029-.258l-.02-.233l-.016-.3c-.081-2.196 1.6-4.329 3.544-5.162a1.47 1.47 0 0 1 1.445.159Zm8.135 3.595l.116.013a3.5 3.5 0 0 1 2.858 2.96a1 1 0 0 1-1.958.393l-.023-.115a1.5 1.5 0 0 0-1.07-1.233l-.155-.035a1 1 0 0 1 .232-1.983ZM15 3a6 6 0 0 1 6 6a1 1 0 0 1-1.993.117L19 9a3.998 3.998 0 0 0-3.738-3.991L15 5a1 1 0 1 1 0-2Z"
                  />
                </g>
              </svg>
            </div>
            <div class="writeup">
              <h4>CALL NOW</h4>
              <p>(234) 803-010-03</p>
            </div>
          </div>
        </div>
        <div class="btn">DONATE NOW</div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.middle-row {
  display: flex;
  flex-direction: row;
  padding: 0 160px;
  margin-top: 50px;
  margin-bottom: 30px;
  justify-content: space-between;
}

.contact{
  display: flex;
  flex-direction: row;
}

#contact-styling {
  display: flex;
  flex-direction: row;
  padding-right: 40px;
}

.logo {
  border: 2px solid #eaeaea;
  border-radius: 100px;
  padding: 17px;
  width: 60px;
}

.writeup {
  padding-left: 15px;
  color: #000;
}

h4,
p {
  font-weight: 500;
}

.btn {
  margin-left: 20px;
  margin-top: 15px;
  height: 40px;
  display: flex;
  justify-content: center;
  align-items: center;
  padding: 10px 25px;
  border: 2px solid #f14b05;
  background-color: #f14b05;
  border-radius: 30px;
  color: #fff;
  font-size: 15px;
  font-weight: 500;
}
.btn:hover {
  background-color: #fff;
  color: #f14b05;
  transition: all 0.3s ease;
}

@media screen and (max-width: 1269px) {
  .middle-row {
    padding: 0 80px;
  }
}

@media screen and (max-width: 1374px) {
  .middle-row {
    padding: 0 30px;
  }
}

@media screen and (max-width: 1085px) {
  .middle-row {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    margin: 20px;
  }
  .contact {
    margin-top: 15px;
  }
}

  @media screen and (max-width: 1082px) {
    .head {
      min-width: 768px;
    }
  }

  @media screen and (max-width: 815px) {
    .contact {
      display: flex;
      flex-direction: column;
    }
    .btn {
      width: 200px;
      margin-left: 170px;
      /* position: absolute;
      top: 208px;
      right: 50%;
      left: 32%; */
    }
  }

  @media screen and (max-width: 768px) {
    .head {
      min-width: 300px;
    }

    #contact-styling {
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
    }

    .writeup {
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
    }

    .btn {
      margin-left: 100px;
    }
  }
  @media screen and (max-width: 524px) {
    h4,p {
      font-size: 12px;
    }

    .btn {
      width: 150px;
      padding: 0;
      margin-left: 80px;
      font-size: 12px;
    }
  }
  @media screen and (max-width: 446px) {
    h4,p {
      font-size: 10px;
    }

    .btn {
      margin-left: 60px;
    }
  }
  @media screen and (max-width: 405px) {
    h4,p {
      font-size: 6px;
    }

    .btn {
      margin-left: 30px;
      font-size: 10px;
    }

    .logo {
      padding: 10px;
    }

    svg {
      margin-left: 8px;
    }

    .writeup {
      margin-top: 5px;
      margin-right: 10px;
    }
  }
</style>
