<template>
  <div class="">
    <div class="container">
      <div>
        <div class="flex justify-between items-center py-5">
          <div class="flex justify-between gap-x-5">
            <img src="../assets/public/logo.png" />
            <h2 class="text-[#46A358] text-[25px] uppercase">greenshop</h2>
          </div>
          <ul class="flex gap-x-[50px]">
            <li>
              <a
                class="hover:font-bold text-[16px] font-normal leading-3 text-[#3D3D3D]"
                >Home</a
              >
            </li>
            <li>
              <a
                class="hover:font-bold text-[16px] font-normal leading-3 text-[#3D3D3D]"
                >Shop</a
              >
            </li>
            <li>
              <a
                class="hover:font-bold text-[16px] font-normal leading-3 text-[#3D3D3D]"
                >Plant Care</a
              >
            </li>
            <li>
              <a
                class="hover:font-bold text-[16px] font-normal leading-3 text-[#3D3D3D]"
                >Blogs</a
              >
            </li>
          </ul>
          <div class="flex w-80px gap-x-[30px]">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              width="30px"
              height="30px"
              viewBox="0 0 512 512"
            >
              <path
                fill="currentColor"
                d="M456.69 421.39L362.6 327.3a173.8 173.8 0 0 0 34.84-104.58C397.44 126.38 319.06 48 222.72 48S48 126.38 48 222.72s78.38 174.72 174.72 174.72A173.8 173.8 0 0 0 327.3 362.6l94.09 94.09a25 25 0 0 0 35.3-35.3M97.92 222.72a124.8 124.8 0 1 1 124.8 124.8a124.95 124.95 0 0 1-124.8-124.8"
              />
            </svg>
            <svg
              xmlns="http://www.w3.org/2000/svg"
              width="30px"
              height="30px"
              viewBox="0 0 56 56"
            >
              <path
                fill="currentColor"
                d="M20.008 39.649H47.36c.913 0 1.71-.75 1.71-1.758s-.797-1.758-1.71-1.758H20.406c-1.336 0-2.156-.938-2.367-2.367l-.375-2.461h29.742c3.422 0 5.18-2.11 5.672-5.461l1.875-12.399a7.2 7.2 0 0 0 .094-.89c0-1.125-.844-1.899-2.133-1.899H14.641l-.446-2.976c-.234-1.805-.89-2.72-3.28-2.72H2.687c-.937 0-1.734.822-1.734 1.76c0 .96.797 1.781 1.735 1.781h7.921l3.75 25.734c.493 3.328 2.25 5.414 5.649 5.414m31.054-25.454L49.4 25.422c-.188 1.453-.961 2.344-2.344 2.344l-29.906.023l-1.993-13.594ZM21.86 51.04a3.766 3.766 0 0 0 3.797-3.797a3.781 3.781 0 0 0-3.797-3.797c-2.132 0-3.82 1.688-3.82 3.797c0 2.133 1.688 3.797 3.82 3.797m21.914 0c2.133 0 3.82-1.664 3.82-3.797c0-2.11-1.687-3.797-3.82-3.797c-2.109 0-3.82 1.688-3.82 3.797c0 2.133 1.711 3.797 3.82 3.797"
              />
            </svg>
            <div class="relative gap-x-[10px] flex w-50px">
              <button
                class="bg-[#46A358] text-[white] pl-[40px] pr-[30px] py-[10px] rounded-md4"
              >
                Login
              </button>
              <a href="#">
                <img
                  class="absolute top-3 left-4"
                  src="../assets/public/Logout.png"
                />
              </a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {};
</script>

<style lang="scss" scoped></style>
