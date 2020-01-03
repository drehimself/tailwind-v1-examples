<template>
  <div class="flex flex-col h-screen text-sm text-gray-400">
    <div class="flex-1 flex overflow-y-hidden">
      <div class="sidebar bg-gray-900-spotify w-48 flex-none flex flex-col justify-between font-semibold">
        <ul class="py-6">
          <li class="border-l-4 border-green-600">
            <a href="#" class="flex items-center mx-4 mt-4 group">
              <svg class="fill-current text-white group-hover:text-white h-6 w-6" viewBox="0 0 24 24" width="24" height="24"><path d="M13 20v-5h-2v5a2 2 0 01-2 2H6a2 2 0 01-2-2v-7.59l-.3.3a1 1 0 11-1.4-1.42l9-9a1 1 0 011.4 0l9 9a1 1 0 01-1.4 1.42l-.3-.3V20a2 2 0 01-2 2h-3a2 2 0 01-2-2zm5 0v-9.59l-6-6-6 6V20h3v-5c0-1.1.9-2 2-2h2a2 2 0 012 2v5h3z"/></svg>
              <span class="ml-2 text-white group-hover:text-white">Home</span>
            </a>
          </li>
          <li class="border-l-4 border-transparent">
            <a href="#" class="flex items-center hover:text-white mx-4 mt-4 group">
              <svg class="fill-current text-gray-400 h-6 w-6 group-hover:text-white" width="24" height="24"><path fill="none" d="M15 5.414V7h1.586z"/><path fill="none" d="M14 9a1 1 0 01-1-1V4H9v12h9V9h-4z"/><path d="M20 17V8h-.009a.996.996 0 00-.284-.707l-5-5A.99.99 0 0014 2.01V2H8a1 1 0 00-1 1v14a1 1 0 001 1h11a1 1 0 001-1zM15 5.414L16.586 7H15V5.414zM9 16V4h4v4a1 1 0 001 1h4v7H9z"/><path d="M3 8v13a1 1 0 001 1h12v-2H5V8H3z"/></svg>
              <span class="ml-2 group-hover:text-white">Browse</span>
            </a>
          </li>
          <li class="border-l-4 border-transparent">
            <a href="#" class="flex items-center hover:text-white mx-4 mt-4 group">
              <svg class="fill-current text-gray-400 h-6 w-6 group-hover:text-white"viewBox="0 0 24 24"><g data-name="Layer 2"><g data-name="radio"><path d="M12 8a3 3 0 00-1 5.83 1 1 0 000 .17v6a1 1 0 002 0v-6a1 1 0 000-.17A3 3 0 0012 8zm0 4a1 1 0 111-1 1 1 0 01-1 1zM3.5 11a6.87 6.87 0 012.64-5.23 1 1 0 10-1.28-1.54A8.84 8.84 0 001.5 11a8.84 8.84 0 003.36 6.77 1 1 0 101.28-1.54A6.87 6.87 0 013.5 11z"/><path d="M16.64 6.24a1 1 0 00-1.28 1.52A4.28 4.28 0 0117 11a4.28 4.28 0 01-1.64 3.24A1 1 0 0016 16a1 1 0 00.64-.24A6.2 6.2 0 0019 11a6.2 6.2 0 00-2.36-4.76zM8.76 6.36a1 1 0 00-1.4-.12A6.2 6.2 0 005 11a6.2 6.2 0 002.36 4.76 1 1 0 001.4-.12 1 1 0 00-.12-1.4A4.28 4.28 0 017 11a4.28 4.28 0 011.64-3.24 1 1 0 00.12-1.4z"/><path d="M19.14 4.23a1 1 0 10-1.28 1.54A6.87 6.87 0 0120.5 11a6.87 6.87 0 01-2.64 5.23 1 1 0 001.28 1.54A8.84 8.84 0 0022.5 11a8.84 8.84 0 00-3.36-6.77z"/></g></g></svg>
              <span class="ml-2 group-hover:text-white2">Radio</span>
            </a>
          </li>
        </ul>

        <div class="sidebar-spotify overflow-y-auto px-5 mt-2">
          <h3 class="uppercase tracking-widest text-gray-500 font-normal text-xs">Your Library</h3>
          <ul class="leading-extra-loose">
            <li class="truncate"><a href="#" class="hover:text-white">Made For You</a></li>
            <li class="truncate"><a href="#" class="hover:text-white">Recently Played</a></li>
            <li class="truncate"><a href="#" class="hover:text-white">Liked Songs</a></li>
            <li class="truncate"><a href="#" class="hover:text-white">Albums</a></li>
            <li class="truncate"><a href="#" class="hover:text-white">Artists</a></li>
            <li class="truncate"><a href="#" class="hover:text-white">Podcasts</a></li>
          </ul>

          <h3 class="uppercase tracking-widest text-gray-500 font-normal text-xs mt-6">Playlists</h3>
          <ul class="leading-extra-loose mb-6">
            <li class="truncate"><a href="#" class="hover:text-white">Acoustic Hits</a></li>
            <li class="truncate"><a href="#" class="hover:text-white">Acoustic Covers</a></li>
            <li class="truncate"><a href="#" class="hover:text-white">Discover Weekly</a></li>
            <li class="truncate"><a href="#" class="hover:text-white">Hot Hits Canada</a></li>
            <li class="truncate"><a href="#" class="hover:text-white">90's Hip-Hop Don't Stop Long Text</a></li>
            <li class="truncate"><a href="#" class="hover:text-white">90s Smash Hits</a></li>
            <li class="truncate"><a href="#" class="hover:text-white">TGIF</a></li>
            <li class="truncate"><a href="#" class="hover:text-white">mint Canada</a></li>
            <li class="truncate"><a href="#" class="hover:text-white">Hip-Hop Central</a></li>
            <li class="truncate"><a href="#" class="hover:text-white">R&amp;B Right Now</a></li>
            <li class="truncate"><a href="#" class="hover:text-white">I Love My '90s R&amp;B</a></li>
            <li class="truncate"><a href="#" class="hover:text-white">Are &amp; Be</a></li>
            <li class="truncate"><a href="#" class="hover:text-white">Today's Top Hits</a></li>
            <li class="truncate"><a href="#" class="hover:text-white">Get Turnt</a></li>
            <li class="truncate"><a href="#" class="hover:text-white">iTunes</a></li>
          </ul>
        </div>
        <div class="border-t border-gray-800 h-16 px-4 py-2 flex items-center group">
          <svg class="fill-current text-gray-600 w-8 h-8 group-hover:text-white" viewBox="0 0 24 24" width="24" height="24"><path class="heroicon-ui" d="M12 22a10 10 0 110-20 10 10 0 010 20zm0-2a8 8 0 100-16 8 8 0 000 16zm1-9h2a1 1 0 010 2h-2v2a1 1 0 01-2 0v-2H9a1 1 0 010-2h2V9a1 1 0 012 0v2z"/></svg>
          <a href="#" class="font-normal text-gray-500 ml-2 group-hover:text-white">New Playlist</a>
        </div>
      </div>
      <div class="content-spotify bg-gray-800-spotify flex-1 overflow-y-auto">content area. Lorem ipsum dolor sit amet consectetur adipisicing elit. A sint iure odit ducimus accusamus veritatis quos obcaecati cupiditate tempora deserunt. Nam deserunt, sunt harum totam consectetur delectus quos officia aspernatur ex sit saepe provident eveniet quidem cumque quaerat odit earum vitae dignissimos nisi quae quo quisquam autem in. Esse consequatur eos ratione soluta tempora voluptates minus cum harum totam quis et voluptas, pariatur temporibus, dolorem mollitia dolor corrupti rem deserunt! Tempore eius quos animi ducimus. Modi iusto temporibus reprehenderit eius. Quas odit vero placeat ipsam esse doloribus fugiat quaerat sunt corporis mollitia debitis ipsa molestias natus quam nesciunt, dolorem dicta soluta quisquam a! Sunt expedita accusamus asperiores molestias illo temporibus dolores rem. Veniam alias harum in sunt dignissimos facilis iure, doloremque odit optio, provident hic aspernatur delectus? Veniam, expedita dolor quisquam eius ipsa, rerum animi vel reiciendis assumenda enim nulla libero doloribus mollitia, id nemo magni labore soluta nisi. Quos nobis sunt voluptatibus ullam consequuntur, consequatur esse voluptates neque non saepe necessitatibus officiis porro magni asperiores reprehenderit doloremque veniam sed. Ab fugit consectetur quos quisquam magnam, vel eum nisi dolorem optio doloremque repellendus nihil beatae, cumque iure laudantium labore eveniet, ducimus dicta! Facilis perferendis deserunt atque iusto fugit necessitatibus voluptate sed rerum qui voluptatum doloremque porro placeat, voluptatem eum tenetur recusandae iure quis? Debitis possimus non quis illo! Fugit quod nulla maiores. Sint quod laboriosam tenetur adipisci exercitationem excepturi alias ipsam nostrum, odit voluptatibus omnis quo natus, quis repudiandae aperiam repellat est dolor eius sapiente ullam. Nostrum quo aut fugit fuga temporibus, in, vero facilis sequi nulla inventore quos dignissimos nam. Eos, enim culpa. Hic error architecto harum, non at rerum minima fuga magnam quod labore maiores omnis incidunt ipsa voluptatum quis deserunt explicabo illo porro sunt esse inventore placeat. Expedita voluptatem quam quaerat numquam. Saepe delectus nesciunt rerum culpa officiis debitis quas id velit impedit doloremque assumenda, a repudiandae aliquid incidunt cum suscipit expedita quasi. Distinctio, consectetur possimus sit, deserunt velit in harum provident voluptatum quae dolore voluptate enim? Numquam, amet provident! Illum commodi similique doloremque sunt iusto! Quam facilis, corrupti minus quasi adipisci inventore sapiente veritatis rerum modi, blanditiis ullam delectus, laborum dolorum? Commodi fugiat accusamus voluptas in aperiam exercitationem culpa quasi, saepe nobis similique ipsa! Suscipit expedita laudantium doloribus. Deserunt dolores facilis quidem! Accusamus perferendis voluptates nesciunt mollitia eos neque veniam, quae soluta voluptatibus molestias quam dolore quidem iste odio porro. Quis, non quae? Cum tempora natus sit atque eos recusandae! Minima recusandae facere dicta autem quaerat eum beatae, ratione quo nam, ullam nostrum in blanditiis error. Tenetur, autem sed ad numquam officiis suscipit nemo earum aut harum enim eaque ratione, veniam in quidem commodi voluptate ducimus. Est laudantium eos quod impedit minus ducimus totam quasi molestiae, voluptas enim, dolorem a cumque quae quibusdam. Accusamus ratione nemo eum praesentium perferendis ut repellendus repudiandae. Velit ea quos totam commodi ducimus rerum saepe praesentium, ut libero vel ipsum, natus nulla officiis eaque, harum et quo iusto exercitationem minus itaque maiores quasi dignissimos? Voluptate consequuntur dolore excepturi repudiandae sapiente cumque necessitatibus praesentium et delectus recusandae ipsam, quaerat a velit similique deserunt neque, eum inventore. Reiciendis, ipsum consequatur laboriosam, in, blanditiis nostrum id voluptatibus cupiditate illum sed at? Voluptatibus, doloribus alias! Necessitatibus nihil fugiat ipsum veniam autem ad illo veritatis temporibus accusamus sit ab quam placeat qui, rerum eaque, molestiae dolorem libero repellendus quo, accusantium molestias a pariatur. Aspernatur neque maiores animi quam velit doloribus itaque! Adipisci aliquid debitis enim! Eius perferendis officia, debitis, placeat aperiam illo illum alias voluptatibus mollitia atque, voluptas aut sequi nemo ab delectus sapiente cumque cupiditate natus ut molestias expedita quam? Incidunt dignissimos perspiciatis ullam debitis laudantium iusto, sequi nesciunt sit autem vitae, unde repellendus labore, iure fugiat corrupti ut eos modi aut quos odit. Velit quaerat ullam illo nemo dolorem qui impedit nobis consequuntur, culpa temporibus corporis omnis facilis iusto vero sequi minus corrupti voluptatum aperiam odio est eaque. Sequi consectetur ab voluptatem fugiat neque facere adipisci atque repellendus, itaque dicta, optio sint fugit quo aliquid officia corrupti porro, quidem molestiae eum modi sit animi fuga rem. Blanditiis, harum eaque cupiditate veritatis dolore aliquid eveniet delectus illo ab ut vitae quas sunt cumque dolores libero ea dolor eius nulla maxime modi. Adipisci dolore, animi nesciunt atque architecto sunt expedita molestias libero illo! Corrupti modi tempore facere dolorum cupiditate distinctio tenetur voluptatibus, molestiae ipsa enim nobis. Sequi porro accusamus voluptatem debitis quos id consequuntur earum quas, cumque quidem deleniti tempora possimus explicabo perferendis error nostrum fugit dolore libero laborum adipisci fugiat? Hic, reiciendis. Dolores voluptatem libero atque corporis eum recusandae blanditiis ratione voluptates accusamus nihil, quidem veritatis quis dolorem magnam asperiores perspiciatis sunt sequi odit hic, voluptas saepe! Nihil dolorum nesciunt, vel amet corporis animi laboriosam at esse odio, eaque perferendis, ex aut iure ut in sint sit autem commodi consequuntur quibusdam tempora? Alias impedit aspernatur aut dolore quis modi quod commodi animi, quia iusto officia, sunt facere deleniti assumenda voluptates consectetur, laboriosam vero? Dolor nihil delectus sint consequatur quibusdam! Facilis atque odio ut earum exercitationem deserunt voluptate libero assumenda, impedit suscipit cupiditate nostrum natus voluptatum ratione sapiente facere eaque. Obcaecati molestiae possimus commodi qui unde numquam, perspiciatis dicta saepe excepturi ducimus ipsum fugit tenetur voluptate voluptatibus eos error corporis inventore, neque temporibus natus adipisci aperiam doloribus. Sed autem quibusdam aliquid. Enim consequatur eum vel tempora, nemo quasi rem voluptate necessitatibus soluta dolores reprehenderit ea voluptas provident sapiente quaerat, optio est adipisci illo natus sint dicta laudantium accusamus! Maxime veritatis, nesciunt sed, nisi excepturi vel odio doloremque dolores sapiente amet ad cumque, dolorem non repudiandae itaque. Odio corrupti tempora explicabo. Nihil eligendi harum fugit quam corrupti veniam! Distinctio fugiat dicta, optio assumenda soluta blanditiis molestiae iste excepturi praesentium fugit beatae dolor rem culpa. Incidunt rerum nostrum veniam officia maiores unde, voluptates ipsa quos molestiae mollitia amet, ipsam exercitationem ab recusandae quas sapiente reprehenderit earum delectus quam, tempore numquam! Labore quasi facilis iusto unde ipsam perferendis provident, modi quo laborum laudantium impedit adipisci tempore consectetur perspiciatis, molestias aut odit earum libero atque quis fuga? Amet distinctio cumque ipsa soluta aperiam adipisci odit quod, perspiciatis aliquam. Quis necessitatibus pariatur unde cum, a vel ipsa eaque facere voluptatibus laborum aperiam doloribus voluptas aliquid at commodi id! Et facere voluptatibus eos aliquid eligendi vitae quo. Ducimus ad, vel repellat recusandae doloribus dolorum harum sint hic libero quis est earum obcaecati temporibus eaque reiciendis voluptatem dolore incidunt odio corrupti quo accusantium deleniti molestias accusamus veniam! Quod voluptatibus quia iusto architecto natus consequatur deleniti temporibus dicta, eligendi laborum! Incidunt corrupti ducimus laborum maiores ab quaerat aliquid culpa cum perferendis, placeat obcaecati assumenda illum illo nisi deserunt ex. Dolor deserunt quaerat voluptate voluptatum exercitationem. Magni commodi ipsum suscipit fuga praesentium exercitationem consequatur accusamus quam totam eveniet nesciunt soluta, veniam pariatur reiciendis necessitatibus reprehenderit repudiandae consectetur fugit laboriosam ab. Hic corporis doloribus accusantium, molestiae error dicta deleniti consequuntur veniam reprehenderit temporibus. Sint optio labore, voluptatibus expedita laboriosam veritatis unde dolorum doloribus nam illum animi perspiciatis dolore architecto. Aperiam et expedita fugit voluptatibus corporis nihil, eveniet numquam natus, iusto recusandae quae facilis modi blanditiis ad omnis. Voluptatibus, fuga deleniti, eligendi necessitatibus laudantium delectus maxime vero optio autem iure voluptatem, reiciendis unde ullam quas porro in ducimus velit totam. Earum est quidem expedita vero saepe totam ea atque ratione? Aut, inventore omnis nesciunt quaerat accusamus error velit neque pariatur, commodi consectetur adipisci accusantium ad perspiciatis ipsam minus facere expedita, aspernatur reiciendis fugit tempora vitae laboriosam! Autem incidunt consequatur pariatur magni? Enim odio fuga, quia explicabo architecto repudiandae nobis at, temporibus eveniet maxime voluptatem sit fugiat harum doloremque dolorem doloribus laudantium nulla placeat atque libero non molestias deserunt porro dignissimos? Molestiae dolorum mollitia ex debitis veniam ullam, esse assumenda. Ex quo libero omnis similique ipsum facilis eaque, voluptatem eveniet harum quia deleniti sint odio accusamus fuga quae eligendi minus quaerat sed maiores perspiciatis voluptas? Libero incidunt, beatae asperiores ipsam dolore aspernatur sapiente perferendis dignissimos. Voluptatibus quae non dolor vitae nulla harum fuga officiis minima molestias cupiditate omnis dolorem error eligendi quibusdam alias beatae, unde perspiciatis asperiores quod iste exercitationem! Quasi nostrum mollitia iste possimus delectus recusandae, ipsa corrupti? Itaque at autem laborum et, mollitia illo ipsam dolore quisquam non vel obcaecati eveniet aperiam quod tempora harum velit quibusdam nobis sapiente atque quae reiciendis officia quas nihil eos. Excepturi fugit tempore, labore itaque et obcaecati omnis exercitationem natus ad, vero quod nam possimus quisquam aut nostrum enim beatae perferendis consequuntur? Sit ipsum, a temporibus repudiandae voluptatem rem reiciendis accusantium pariatur sed quisquam quibusdam vero repellendus esse tenetur, eveniet odio expedita voluptatum ut, in nisi corporis. Iusto id ipsam excepturi voluptas consectetur eius, quidem iure, accusamus dicta obcaecati quia explicabo exercitationem eveniet itaque expedita doloremque non illo nemo quisquam soluta ut est repudiandae eum. Laboriosam enim aut dicta mollitia totam quidem, maxime repudiandae nulla. Minus libero tempore ad quo qui quos deleniti provident fuga mollitia quibusdam, accusamus ut exercitationem totam nam nobis possimus molestias quod cum quaerat velit eveniet minima nihil. Explicabo rem, quasi ipsa iusto itaque aspernatur dolor veritatis! Quisquam delectus, rerum architecto animi esse ipsa et veniam, modi non distinctio fuga iusto neque nostrum alias! Voluptatibus, eos obcaecati porro rerum, pariatur corporis et quo sequi cupiditate libero laboriosam repudiandae facilis. Modi porro quasi tempore et odit voluptatibus accusantium atque in quam commodi aliquid minus debitis, rem provident consequatur maxime. Dolore quo quod nam sint ipsam eligendi minima rem, pariatur voluptatem eum dolorem iusto dicta alias eos voluptate nulla atque. Qui impedit soluta sit enim fuga atque. Esse, perferendis quasi animi nihil debitis veniam beatae! Earum nam magnam maxime cum rem ex modi facilis enim ea aliquam, omnis doloribus consequuntur alias, molestiae autem voluptate molestias natus neque eos at debitis? Doloribus tempore, assumenda officia laboriosam sint expedita quasi nemo! Delectus qui laudantium repellat eum ratione laborum voluptatum quas molestias architecto itaque adipisci obcaecati non corrupti animi voluptates, inventore reiciendis suscipit, minima, aut nobis! Vel cum ipsa optio. Illum magnam id optio expedita sunt alias fugit consequatur fuga? Molestias ad eaque mollitia corporis, tempora, deserunt, ullam magnam obcaecati alias quae quis commodi odio similique hic. Quis eligendi saepe facilis. Earum expedita inventore beatae autem sequi est maxime ex illo minima, ratione adipisci corporis illum nemo accusamus cupiditate numquam officiis. Obcaecati officiis pariatur quisquam, reiciendis eaque nesciunt nemo velit possimus quos beatae omnis impedit explicabo, sint tempore atque itaque architecto qui vero? Omnis quasi similique harum ipsa reprehenderit ducimus autem quis mollitia vero, officia, in explicabo debitis a! Nemo, iure recusandae eaque libero magni sequi ipsum, deleniti ipsam repudiandae harum fugiat expedita illum itaque. Est voluptas at necessitatibus voluptate fuga quam blanditiis totam asperiores quisquam. Voluptatum temporibus dolorum possimus, totam architecto incidunt quis, eligendi inventore minus veniam quisquam. Sint obcaecati numquam ad perferendis dolorum, expedita aliquid, ipsam pariatur esse laudantium suscipit odio distinctio enim placeat fugiat minus consequuntur exercitationem fugit culpa officia. Doloremque aliquid, nesciunt consequuntur vitae asperiores ad quod magnam omnis explicabo adipisci deleniti ullam ex velit neque sunt dignissimos. Eligendi esse est laboriosam eos alias autem harum porro, maiores reiciendis, quis molestias, qui officia iusto odit quae! Sapiente dolorum unde nobis fugiat, provident dignissimos mollitia similique officiis, modi magnam vitae ipsa ab rem quas deleniti, iste quo? Voluptas in cupiditate laborum debitis quisquam officia animi quod consectetur id assumenda eum ullam aliquam, explicabo fugiat cum consequuntur porro cumque alias inventore. Saepe aspernatur sapiente a consequuntur est praesentium, repudiandae voluptatibus ut qui at. Laboriosam facere, ipsum fugit facilis veritatis atque ratione alias. Quam nihil temporibus, sint recusandae doloribus distinctio dolorum dolorem quasi, voluptatum laboriosam consequatur excepturi consectetur minima molestiae, sunt voluptatibus fuga architecto enim adipisci mollitia! Nemo distinctio eveniet temporibus facere sit error eaque facilis, blanditiis illum quaerat labore sunt quae corrupti cupiditate voluptates? Deserunt aperiam molestias possimus dolorum beatae! Natus cumque quo inventore cum laborum consectetur alias possimus non ad quia? Totam libero quaerat ea reiciendis voluptatibus nisi quam repudiandae mollitia eius excepturi eligendi et velit neque, sint atque nemo voluptatum molestiae dolorem esse. Quis sunt magni minima veritatis ratione eius. Blanditiis voluptatem atque aperiam corrupti dolorem deleniti incidunt ratione consectetur quis magni, voluptatibus, quaerat id delectus molestiae.</div>
    </div>
    <div class="bg-gray-700-spotify flex-none h-22 px-5 flex items-center justify-between">
      <div class="flex items-center">
        <a href="#"><img src="albumcover01.jpg" alt="album cover" class="w-14 h-14"></a>
        <div class="ml-3">
          <div><a href="#" class="hover:underline">Name of Song</a></div>
          <div><a href="#" class="text-xs text-gray-500 hover:underline hover:text-white">Artist Name</a></div>
        </div>
      </div>
      <div class="player-controls flex flex-col justify-center">
        <div class="flex justify-center">
          <button>
            <svg class="fill-current text-gray-400 hover:text-white h-4 w-4" viewBox="0 0 20 20"><path d="M6.59 12.83L4.4 15c-.58.58-1.59 1-2.4 1H0v-2h2c.29 0 .8-.2 1-.41l2.17-2.18 1.42 1.42zM16 4V1l4 4-4 4V6h-2c-.29 0-.8.2-1 .41l-2.17 2.18L9.4 7.17 11.6 5c.58-.58 1.59-1 2.41-1h2zm0 10v-3l4 4-4 4v-3h-2c-.82 0-1.83-.42-2.41-1l-8.6-8.59C2.8 6.21 2.3 6 2 6H0V4h2c.82 0 1.83.42 2.41 1l8.6 8.59c.2.2.7.41.99.41h2z"/></svg>
          </button>
          <button class="ml-8">
            <svg class="fill-current text-gray-400 hover:text-white h-6 w-6" viewBox="0 0 20 20"><path d="M4 5h3v10H4V5zm12 0v10l-9-5 9-5z"/></svg>
          </button>
          <button class="ml-8">
            <svg class="fill-current text-gray-400 hover:text-white h-8 w-8" viewBox="0 0 20 20"><path d="M2.93 17.07A10 10 0 1117.07 2.93 10 10 0 012.93 17.07zm12.73-1.41A8 8 0 104.34 4.34a8 8 0 0011.32 11.32zM7 6l8 4-8 4V6z"/></svg>
          </button>
          <button class="ml-8">
            <svg class="fill-current text-gray-400 hover:text-white h-6 w-6" viewBox="0 0 20 20"><path d="M13 5h3v10h-3V5zM4 5l9 5-9 5V5z"/></svg>
          </button>
          <button class="ml-8">
            <svg class="fill-current text-gray-400 hover:text-white h-4 w-4" viewBox="0 0 24 24" width="24" height="24"><path d="M5.41 16H18a2 2 0 002-2 1 1 0 012 0 4 4 0 01-4 4H5.41l2.3 2.3a1 1 0 01-1.42 1.4l-4-4a1 1 0 010-1.4l4-4a1 1 0 111.42 1.4L5.4 16zM6 8a2 2 0 00-2 2 1 1 0 01-2 0 4 4 0 014-4h12.59l-2.3-2.3a1 1 0 111.42-1.4l4 4a1 1 0 010 1.4l-4 4a1 1 0 01-1.42-1.4L18.6 8H6z"/></svg>
          </button>
        </div>
        <div class="max-w-full mt-3 flex items-center justify-center">
          <div class=" text-xs text-gray-500">1:20</div>
          <div class="bg-gray-500 rounded-lg w-full xl:w-200 h-1 ml-3"></div>
          <div class="ml-3 text-xs text-gray-500">3:21</div>
        </div>
      </div>
      <div class="volume-controls flex items-center">
        <button>
          <svg class="fill-current text-gray-400 hover:text-white h-6 w-6" width="24" height="24" viewBox="0 0 24 24"><path d="M0 0h24v24H0z" fill="none"/><path d="M15 6H3v2h12V6zm0 4H3v2h12v-2zM3 16h8v-2H3v2zM17 6v8.18c-.31-.11-.65-.18-1-.18-1.66 0-3 1.34-3 3s1.34 3 3 3 3-1.34 3-3V8h3V6h-5z"/></svg>
        </button>
        <button class="ml-4">
          <svg class="fill-current text-gray-400 hover:text-white h-5 w-5" width="24" height="24" viewBox="0 0 24 24"><path fill="none" d="M0 0h24v24H0z"/><path d="M3 6h18V4H3c-1.1 0-2 .9-2 2v12c0 1.1.9 2 2 2h4v-2H3V6zm10 6H9v1.78c-.61.55-1 1.33-1 2.22s.39 1.67 1 2.22V20h4v-1.78c.61-.55 1-1.34 1-2.22s-.39-1.67-1-2.22V12zm-2 5.5c-.83 0-1.5-.67-1.5-1.5s.67-1.5 1.5-1.5 1.5.67 1.5 1.5-.67 1.5-1.5 1.5zM22 8h-6c-.5 0-1 .5-1 1v10c0 .5.5 1 1 1h6c.5 0 1-.5 1-1V9c0-.5-.5-1-1-1zm-1 10h-4v-8h4v8z"/></svg>
        </button>
        <button class="ml-4">
          <svg class="fill-current text-gray-400 hover:text-white h-5 w-5" width="24" height="24" viewBox="0 0 24 24"><path d="M3 9v6h4l5 5V4L7 9H3zm13.5 3A4.5 4.5 0 0014 7.97v8.05c1.48-.73 2.5-2.25 2.5-4.02zM14 3.23v2.06c2.89.86 5 3.54 5 6.71s-2.11 5.85-5 6.71v2.06c4.01-.91 7-4.49 7-8.77s-2.99-7.86-7-8.77z"/><path d="M0 0h24v24H0z" fill="none"/></svg>
        </button>
        <div class="bg-gray-500 rounded-lg w-20 h-1 ml-3"></div>
        <button class="ml-4">
          <svg class="fill-current text-gray-400 hover:text-white h-4 w-4" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M15 3h6v6M9 21H3v-6M21 3l-7 7M3 21l7-7"/></svg>
        </button>
      </div>
    </div>
  </div>
</template>

<style>
  .sidebar-spotify::-webkit-scrollbar
  {
    width: 8px;
    background-color: #121212;
  }

  .sidebar-spotify::-webkit-scrollbar-thumb {
    border-radius: 8px;
    background-color: #535353;
  }

  .content-spotify::-webkit-scrollbar
  {
    width: 8px;
    background-color: #181818;
  }

  .content-spotify::-webkit-scrollbar-thumb {
    border-radius: 8px;
    background-color: #535353;
  }
</style>
