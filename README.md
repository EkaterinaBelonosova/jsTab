Скрипт нужен для переключения табов.
Табы зависят от 3х элементов/классов на странице.(на примере верстки ниже)
Класс с реальными табами, которые будут служить для переключения нужно подставить в 
	tab = document.querySelectorAll('.нашкласс');
 и в обработчик события 
 if (target && target.classList.contains('нашкласс')).

Блок или класс с табами помещается
info = document.querySelector('.нашкласс').

И класс контента, который будет переключаться между табами:
tabContant = document.querySelectorAll('.нашкласс');
	

		<div class="info" >
				<div class="info-header">
					<div class="info-header-tab">Лечение</div>
					<div class="info-header-tab">Отдых</div>
					<div class="info-header-tab">Природа</div>
					<div class="info-header-tab">Йога</div>
				</div>
				<div class="info-tabcontent fade">
					<div class="description">
						<div class="description-title">Здоровый позвоночник</div>
					</div>
				</div>
				<div class="info-tabcontent fade">
					<div class="description">
						<div class="description-title">Антистресс</div>
					</div>
				</div>
				<div class="info-tabcontent fade">
					<div class="description">
						<div class="description-title">Восстановление</div>
					</div>
				</div>
				<div class="info-tabcontent fade">
					<div class="description">
						<div class="description-title">Йога и аюрведа</div>
					</div>
				</div>
			</div>
