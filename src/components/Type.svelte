<div class="overflow-visible sticky top-0 z-10 p-4">
    <h2 class= TYPE>
        <slot>Type</slot>
    </h2>
  </div>
  
  <style>
    .TYPE {
        color: #fffffe;
        font-weight: normal;
        text-transform: uppercase;
        overflow: hidden; 
        border-right: .10em solid white; 
        white-space: nowrap; 
        margin: 0 auto; 
        margin-top: 10px;
        margin-bottom: 10px;
        letter-spacing: .10em; 
        font-size: 60px;
        animation: typing 5s steps(19, end), blink-caret 0.4s step-end infinite; 
        animation-iteration-count: infinite; 
    }
    @keyframes typing {
        from { width: 0 }
        to { width: 10em; }
    }

    @keyframes blink-caret {
        from, to { border-color: transparent }
        50% { border-color: #eebbc3 }
    }

  </style>