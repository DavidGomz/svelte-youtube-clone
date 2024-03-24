<script>
    import '../app.css'
    import SearchBar from './SearchBar.svelte'
    import logo from './icons/ytb-logo.webp'
    import bugerIcon from './icons/bugerIcon.svg'
    import createIcon from './icons/createIcon.svg'
    import notIcon from './icons/notIcon.svg'
    import avatar from './icons/profile.jpg'
</script>

<header class="flex px-4 py-2 items-center h-[64px] bg-white z-10 justify-between sticky top-0 left-0">
    <div class="flex gap-4 items-center ">
        <img src={bugerIcon} alt="" class="p-3 rounded-full hover:bg-gray-200 cursor-pointer">
        <img src={logo} alt="" class="h-[56px]">
        
    </div>
    <div class="border-black">
        <SearchBar />
    </div>

    <div class="flex gap-3 items-center">
        <img src={createIcon} alt="" class="p-3 rounded-full hover:bg-gray-200 cursor-pointer" />
        <img src={notIcon} alt="" class="p-3 rounded-full hover:bg-gray-200 cursor-pointer" />
        <img src={avatar} alt="" class="bg-gray-200 h-8 w-8 rounded-full cursor-pointer" />
    </div>
</header>