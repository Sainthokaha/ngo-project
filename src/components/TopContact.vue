<template>
  <div class="head">
    <div class="top-social">
      <div class="top-social-left">
        Support Us: <span>companyname@gmail.com</span>
      </div>
      <div class="top-social-right">
        <a href="http://" target="_blank" rel="noopener noreferrer">
          <svg :fill="isHovered ? 'white' : '#9C9C9C'" xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><path d="M9.198 21.5h4v-8.01h3.604l.396-3.98h-4V7.5a1 1 0 0 1 1-1h3v-4h-3a5 5 0 0 0-5 5v2.01h-2l-.396 3.98h2.396v8.01Z"/></svg>
        </a>
        <a href="http://" target="_blank" rel="noopener noreferrer">
          <svg :fill="isHovered ? 'white' : '#9C9C9C'" xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><path d="M22.46 6c-.77.35-1.6.58-2.46.69c.88-.53 1.56-1.37 1.88-2.38c-.83.5-1.75.85-2.72 1.05C18.37 4.5 17.26 4 16 4c-2.35 0-4.27 1.92-4.27 4.29c0 .34.04.67.11.98C8.28 9.09 5.11 7.38 3 4.79c-.37.63-.58 1.37-.58 2.15c0 1.49.75 2.81 1.91 3.56c-.71 0-1.37-.2-1.95-.5v.03c0 2.08 1.48 3.82 3.44 4.21a4.22 4.22 0 0 1-1.93.07a4.28 4.28 0 0 0 4 2.98a8.521 8.521 0 0 1-5.33 1.84c-.34 0-.68-.02-1.02-.06C3.44 20.29 5.7 21 8.12 21C16 21 20.33 14.46 20.33 8.79c0-.19 0-.37-.01-.56c.84-.6 1.56-1.36 2.14-2.23Z"/></svg>
        </a>
        <a href="http://" target="_blank" rel="noopener noreferrer">
          <svg :fill="isHovered ? 'white' : '#9C9C9C'" xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><path d="M23 11h-2V9h-2v2h-2v2h2v2h2v-2h2M8 11v2.4h4c-.2 1-1.2 3-4 3c-2.4 0-4.3-2-4.3-4.4c0-2.4 1.9-4.4 4.3-4.4c1.4 0 2.3.6 2.8 1.1l1.9-1.8C11.5 5.7 9.9 5 8 5c-3.9 0-7 3.1-7 7s3.1 7 7 7c4 0 6.7-2.8 6.7-6.8c0-.5 0-.8-.1-1.2H8Z"/></svg>
        </a>
        <a href="http://" target="_blank" rel="noopener noreferrer">
          <svg :fill="isHovered ? 'white' : '#9C9C9C'" xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><path d="M6.94 5a2 2 0 1 1-4-.002a2 2 0 0 1 4 .002ZM7 8.48H3V21h4V8.48Zm6.32 0H9.34V21h3.94v-6.57c0-3.66 4.77-4 4.77 0V21H22v-7.93c0-6.17-7.06-5.94-8.72-2.91l.04-1.68Z"/></svg>
        </a>
        <a href="http://" target="_blank" rel="noopener noreferrer">
          <svg :fill="isHovered ? 'white' : '#9C9C9C'" xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><path d="M9.04 21.54c.96.29 1.93.46 2.96.46a10 10 0 0 0 10-10A10 10 0 0 0 12 2A10 10 0 0 0 2 12c0 4.25 2.67 7.9 6.44 9.34c-.09-.78-.18-2.07 0-2.96l1.15-4.94s-.29-.58-.29-1.5c0-1.38.86-2.41 1.84-2.41c.86 0 1.26.63 1.26 1.44c0 .86-.57 2.09-.86 3.27c-.17.98.52 1.84 1.52 1.84c1.78 0 3.16-1.9 3.16-4.58c0-2.4-1.72-4.04-4.19-4.04c-2.82 0-4.48 2.1-4.48 4.31c0 .86.28 1.73.74 2.3c.09.06.09.14.06.29l-.29 1.09c0 .17-.11.23-.28.11c-1.28-.56-2.02-2.38-2.02-3.85c0-3.16 2.24-6.03 6.56-6.03c3.44 0 6.12 2.47 6.12 5.75c0 3.44-2.13 6.2-5.18 6.2c-.97 0-1.92-.52-2.26-1.13l-.67 2.37c-.23.86-.86 2.01-1.29 2.7v-.03Z"/></svg>
        </a>
      </div>
    </div>
    <div class="top-contact">

    </div>
  </div>
</template>

<script>
  export default {
    data() {
      return {
        isHovered: false
      }
    },
    methods: {
      onMouseEnter() {
        this.isHovered = true;
      },
      onMouseLeave() {
        this.isHovered = false;
      }
    }
  }
</script>

<style scoped>
  .head {
    width: 100%;
  }
  .top-social {
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: center;
    padding: 0 160px;
    border-bottom: 1px solid #EAEAEA; 
  }

  .top-social-right a:first-child {
    border-left: 1px solid #EAEAEA;
  }

  .top-social-right {
    display: flex;
    flex-direction: row;
    
  }

  .top-social-right a{
    border-right: 1px solid #EAEAEA;
    height: 50px;
    display: flex;
    justify-content: center;
    align-items: center;
    padding: 0 9px;
    padding-top: 5px;
    transition: all .3s ease;
  }

  .top-social-right a:hover {
    background-color: #f14b05;
  }

  .top-social-right a:hover svg {
    fill: white;
  }

  @media screen and (max-width: 1269px) {
    .top-social {
      padding: 0 80px;
    }
  }

  @media screen and (max-width: 1374px) {
    .top-social {
      padding: 0 30px;
    }
  }
  /* @media screen and (min-width: 768px) {
    .head {
      min-width: 1082px;
    }
  } */
  @media screen and (max-width: 1082px) {
    .head {
      min-width: 768px;
    
    }
  }
  @media screen and (max-width: 768px) {
    .head {
      min-width: 557px;
    }
  }

  @media screen and (max-width: 557px) {
    .head {
      min-width: 100px;
    }

    .top-social {
      display: flex;
      flex-direction: column;
    }

    .top-social-right {
      margin-top: 15px;
    }

    .top-social-right a {
      border-top: 1px solid #EAEAEA;
    }
  }
  @media screen and (max-width: 340px) {
    .top-social-left {
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
    }
  }
</style>