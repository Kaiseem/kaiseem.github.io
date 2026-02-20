<h1 id="news"></h1>
<h2 style="margin: 30px 0px 10px;">News</h2>

<script type="text/javascript">
  function toggle_more() {
    var items = document.getElementsByClassName('more-news-item');
    var link = document.getElementById('toggle-link');
    
    for(var i = 0; i < items.length; i++) {
      if (items[i].style.display == 'none' || items[i].style.display == '') {
        items[i].style.display = 'list-item';
      } else {
        items[i].style.display = 'none';
      }
    }
    if (link.innerHTML == 'show more') {
      link.innerHTML = 'show less';
    } else {
      link.innerHTML = 'show more';
    }
  }
</script>

<ul>
  <!-- 可见的新闻条目 -->
  <li><strong>[JAN. 2026]</strong> Our conference paper accepted in EACL 2026 as Oral presentation.</li> 
  <li><strong>[SEG. 2025]</strong> Our paper accepted in IJCV and ACM MM 2025.</li> 
  <li><strong>[AUG. 2025]</strong> Our conference paper accepted in CIKM 2025.</li> 
  <li><strong>[APR. 2025]</strong> Our conference paper accepted in ACL 2025.</li> 
  <li><strong>[DEC. 2024]</strong> Our conference paper accepted in AAAI 2025 as Oral presentation.</li> 
  <li><strong>[NOV. 2024]</strong> I am happy to attend EMNLP 2024 in person at Miami.</li> 
  <li><strong>[SEP. 2024]</strong> Our conference paper accepted in EMNLP24.</li>
  <li><strong>[DEC. 2023]</strong> Our conference paper accepted in AAAI24.</li> 
  
  <!-- 隐藏的新闻条目（初始状态为隐藏） -->
  <li class="more-news-item" style="display:none;">[Aug. 2023] Our papers accepted as Oral Presentation in ACM CIKM 2023.</li>
  <li class="more-news-item" style="display:none;">[May. 2023] Our two journal papers accepted in IEEE TETCI and IJB.</li>
  <li class="more-news-item" style="display:none;">[Nov. 2022] Our conference paper accepted in AAAI 2023. We propose a novel augmentation for medical image domain generalization. The code released at <a href="https://github.com/Kaiseem/SLAug">here</a>.</li>
  <li class="more-news-item" style="display:none;">[Jul. 2022] Our conference paper accepted in ECCV 2022. We propose a novel hybrid vision-transformer-based GAN for image outpainting. The code released at <a href="https://github.com/Kaiseem/QueryOTR">here</a>.</li>
  <li class="more-news-item" style="display:none;">[Jun. 2022] Our journal paper accepted in IEEE-JBHI (IF: 7.0).</li>
  <li class="more-news-item" style="display:none;">[Dec. 2021] Our team PremiLab wins 5th in the Challenge <a href="https://www.sciencedirect.com/science/article/pii/S1361841522002560">CrossMoDa 2021 (MICCAI workshop)</a>.</li>
  <li class="more-news-item" style="display:none;">[Dec. 2021] Our journal paper accepted in International Journal of Bioprinting (IF: 7.4).</li>
  <li class="more-news-item" style="display:none;">[Nov. 2021] Our journal paper accepted in Cognitive Computation (IF: 4.9).</li>
  <li class="more-news-item" style="display:none;">[Dec. 2019] I started my PhD course at UoL PremiLab Lab with full scholarship.</li>
  
  <!-- "show more/less" 链接 -->
  <li><a href="javascript:toggle_more()" id="toggle-link">show more</a></li>
</ul>