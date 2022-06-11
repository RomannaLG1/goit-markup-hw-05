# фіксоване меню і паддінг на боді
        position: fixed;
	width: 100%;
	background-color: rgba(255, 255, 255, 0.1);
	top: 0;
	left: 0;
	z-index: 10;
	
#modal window js
(() => {
  const refs = {
    openModalBtn: document.querySelector('[data-modal-open]'),
    closeModalBtn: document.querySelector('[data-modal-close]'),
    modal: document.querySelector('[data-modal]'),
  };

  refs.openModalBtn.addEventListener('click', toggleModal);
  refs.closeModalBtn.addEventListener('click', toggleModal);

  function toggleModal() {
    refs.modal.classList.toggle('is-hidden');
  }
})();
