<script>
import { RouterLink, RouterView } from 'vue-router'

</script>

<template>

  <!-- Marketing messaging and featurettes
  ================================================== -->
  <!-- Wrap the rest of the page in another container to center all the content. -->

  <div class="content-head speakers__head"><!-- BEGIN content-head__row content-head__row_title -->
    <div class="content-head__row content-head__row_title">
      <div class="layout-container mobile_no-gutter">
        <div class="content-head__inner">
          <h1 class="main-title">Спикеры</h1>
          <form class="content-head__filter inner-center" name="_form" action="/speakers/" method="get">
            <div class="bx-filter-select-block field-select custom-select">
              <div class="jq-selectbox__select">
                <div class="bx-filter-select-text jq-selectbox__select-text" data-role="currentOption">
                  <span class="bx-filter-parameters-box-hint">География:</span> Все 
                </div>
              </div>
            </div>
            <div class="bx-filter-select-block field-select custom-select custom-select_lang">
              <div class="jq-selectbox__select">
                <div class="bx-filter-select-text jq-selectbox__select-text" data-role="currentOption">
                  <span class="bx-filter-parameters-box-hint">Язык:</span> Все 
                </div>
              </div>
            </div>
            <label data-role="label_arrFilter_61_3233089245" class="bx_filter_param_label custom-cbx checkbox" for="arrFilter_61_3233089245">
              <input type="checkbox" name="arrFilter_61_3233089245" id="arrFilter_61_3233089245" value="Y">
              <span class="checkbox__text">TOP-50 </span>
            </label>
            <label data-role="label_arrFilter_65_3233089245" class="bx_filter_param_label custom-cbx checkbox" for="arrFilter_65_3233089245">
              <input type="checkbox" name="arrFilter_65_3233089245" id="arrFilter_65_3233089245" value="Y">
              <span class="checkbox__text">Золотой спикер </span>
            </label>
          </form>
        </div>
      </div>
    </div>
    </div>

  <div class="content-search">
				<div class="layout-container">

					<form class="content-search__form" action="" method="get">

						<input type="submit" value="">
						<input type="text" name="q" placeholder="Найти спикера" value="" size="40">
						<input type="hidden" name="how" value="r">

					</form>

					
				</div>
	</div>

  <div class="container-lg">
    <div class="row row-cols-1 row-cols-sm-2 row-cols-md-4 g-4">
      <div class="col">
        <div class="card shadow-sm">
          <img class="image-post" src="https://www.topspeaker.ru/upload/iblock/c86/eae5ki567erhic55jm60rkgta82h1q8c.jpg" alt="" loading="lazy">
          <div class="overlay">
            <div class="card-body">
              <RouterLink to="/about">
                <h5 class="card-title text">Иван Коршунов</h5>
              </RouterLink>
              <a href="#" class="card-link">
				        Художники / Искусствоведы			
              </a>
              <p class="card-text text">Кандидат искусствоведения, художник, член Московского союза художников</p>
              <p class="card-text text"><i class="bi bi-globe-asia-australia" style="color: #41aafe;"></i>
                <small class="text-muted text">
					        Русский				
                </small>
              </p>
            </div>
          </div>
        </div>
      </div>
      <div class="col">
        <div class="card shadow-sm">
          <img class="image-post" src="https://www.topspeaker.ru/upload/iblock/c86/eae5ki567erhic55jm60rkgta82h1q8c.jpg" alt="" loading="lazy">
          <div class="overlay">
            <div class="card-body">
              <h5 class="card-title text">Иван Коршунов</h5>
              <a href="#" class="card-link">
				        Художники / Искусствоведы			
              </a>
              <p class="card-text text">Кандидат искусствоведения, художник, член Московского союза художников</p>
              <p class="card-text text"><i class="bi bi-globe-asia-australia" style="color: #41aafe;"></i>
                <small class="text-muted text">
					        Русский				
                </small>
              </p>
            </div>
          </div>
        </div>
      </div>
      <div class="col">
        <div class="card shadow-sm">
          <img class="image-post" src="https://www.topspeaker.ru/upload/iblock/c86/eae5ki567erhic55jm60rkgta82h1q8c.jpg" alt="" loading="lazy">
          <div class="overlay">
            <div class="card-body">
              <h5 class="card-title text">Иван Коршунов</h5>
              <a href="#" class="card-link">
				        Художники / Искусствоведы			
              </a>
              <p class="card-text text">Кандидат искусствоведения, художник, член Московского союза художников</p>
              <p class="card-text text"><i class="bi bi-globe-asia-australia" style="color: #41aafe;"></i>
                <small class="text-muted text">
					        Русский				
                </small>
              </p>
            </div>
          </div>
        </div>
      </div>
      <div class="col">
        <div class="card shadow-sm">
          <img class="image-post" src="https://www.topspeaker.ru/upload/iblock/c86/eae5ki567erhic55jm60rkgta82h1q8c.jpg" alt="" loading="lazy">
          <div class="overlay">
            <div class="card-body">
              <h5 class="card-title text">Иван Коршунов</h5>
              <a href="#" class="card-link">
				        Художники / Искусствоведы			
              </a>
              <p class="card-text text">Кандидат искусствоведения, художник, член Московского союза художников</p>
              <p class="card-text text"><i class="bi bi-globe-asia-australia" style="color: #41aafe;"></i>
                <small class="text-muted text">
					        Русский				
                </small>
              </p>
            </div>
          </div>
        </div>
      </div>
      <div class="col">
        <div class="card shadow-sm">
          <img class="image-post" src="https://www.topspeaker.ru/upload/iblock/c86/eae5ki567erhic55jm60rkgta82h1q8c.jpg" alt="" loading="lazy">
          <div class="overlay">
            <div class="card-body">
              <h5 class="card-title text">Иван Коршунов</h5>
              <a href="#" class="card-link">
				        Художники / Искусствоведы			
              </a>
              <p class="card-text text">Кандидат искусствоведения, художник, член Московского союза художников</p>
              <p class="card-text text"><i class="bi bi-globe-asia-australia" style="color: #41aafe;"></i>
                <small class="text-muted text">
					        Русский				
                </small>
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
