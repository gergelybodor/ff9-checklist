<script lang="ts">
  import Checkbox from '$lib/components/Checkbox.svelte';
</script>

<div class="flex flex-col gap-8 text-xs">
  <h3 class="text-2xl">Alexandria Castle (<span class="text-error">Disc 2 Only</span>)</h3>

  <div class="rounded-box border-base-content/5 bg-base-100 overflow-x-auto border">
    <table class="table-xs table">
      <colgroup>
        <col style="width: 5%" />
        <col style="width: 20%" />
        <col style="width: 20%" />
        <col style="width: 55%" />
      </colgroup>
      <thead>
        <tr>
          <th></th>
          <th>Item</th>
          <th>Category</th>
          <th>Location</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td><Checkbox id="t-2-1" /></td>
          <td>Tent</td>
          <td><strong><span class="text-category-treasure-chest">Treasure Chest</span></strong></td>
          <td>
            As you're descending the Castle interior during the story events to find Dagger, the
            Tent can be found in a chest off on a lone platform.
          </td>
        </tr>
        <tr>
          <td><Checkbox id="t-2-2" /></td>
          <td>Ice Brand</td>
          <td><strong><span class="text-category-treasure-chest">Treasure Chest</span></strong></td>
          <td>
            As you're descending the Castle interior during the story events to find Dagger, this
            item the can be found in a chest off on a lone platform.
          </td>
        </tr>
      </tbody>
    </table>
  </div>

  <h3 class="text-2xl">The Village of Dali (<span class="text-error">Disc 2 Only</span>)</h3>

  <div class="rounded-box border-base-content/5 bg-base-100 overflow-x-auto border">
    <table class="table-xs table">
      <colgroup>
        <col style="width: 5%" />
        <col style="width: 20%" />
        <col style="width: 20%" />
        <col style="width: 55%" />
      </colgroup>
      <thead>
        <tr>
          <th></th>
          <th>Item</th>
          <th>Category</th>
          <th>Location</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td><Checkbox id="t-2-3" /></td>
          <td>Elixir</td>
          <td><strong><span class="text-category-treasure-chest">Treasure Chest</span></strong></td>
          <td>
            Inside the <strong><em>field of crops</em></strong>, the elixir can be found between two
            of the rows of the aforementioned crops.
          </td>
        </tr>
      </tbody>
    </table>
  </div>

  <h3 class="text-2xl">Lindblum (<span class="text-error">Disc 2 Only</span>)</h3>

  <div class="rounded-box border-base-content/5 bg-base-100 overflow-x-auto border">
    <table class="table-xs table">
      <colgroup>
        <col style="width: 5%" />
        <col style="width: 20%" />
        <col style="width: 20%" />
        <col style="width: 55%" />
      </colgroup>
      <thead>
        <tr>
          <th></th>
          <th>Item</th>
          <th>Category</th>
          <th>Location</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td><Checkbox id="t-2-4" /></td>
          <td>Ether</td>
          <td><strong><span class="text-category-treasure-chest">Treasure Chest</span></strong></td>
          <td>
            This can be found inside <strong><em>Gon the Card Freak's House</em></strong>.<br /></td
          >
        </tr>
        <tr>
          <td><Checkbox id="t-2-5" /></td>
          <td>Phoenix Pinion</td>
          <td><strong><span class="text-category-treasure-chest">Treasure Chest</span></strong></td>
          <td>
            This can be found inside <strong><em>Gon the Card Freak's House</em></strong>.<br /></td
          >
        </tr>
        <tr>
          <td><Checkbox id="t-2-6" /></td>
          <td>Bandana</td>
          <td><strong><span class="text-category-treasure-chest">Treasure Chest</span></strong></td>
          <td>
            This can be found behind the <strong
              ><em>small elevated platform at Dragon's Gate.</em></strong
            >
          </td>
        </tr>
        <tr>
          <td><Checkbox id="t-2-7" /></td>
          <td>Ore</td>
          <td><strong><span class="text-category-treasure-chest">Treasure Chest</span></strong></td>
          <td>
            This can be found inside the <strong><em>Art Studio that's owned by Michael</em></strong
            >.
          </td>
        </tr>
        <tr>
          <td><Checkbox id="t-2-8" /></td>
          <td>Lindblum Tetra Card</td>
          <td><strong><span class="text-category-field-icon">Field Icon</span></strong></td>
          <td>
            This can be found inside the debris that's near <strong
              ><em>Gon the Card Freak's House.</em></strong
            >
          </td>
        </tr>
        <tr>
          <td><Checkbox id="t-2-9" /></td>
          <td>262 Gil</td>
          <td><strong><span class="text-category-treasure-chest">Treasure Chest</span></strong></td>
          <td>This can be found <strong><em>inside the Tentalus Playhouse.</em></strong></td>
        </tr>
        <tr>
          <td><Checkbox id="t-2-10" /></td>
          <td>340 Gil</td>
          <td><strong><span class="text-category-treasure-chest">Treasure Chest</span></strong></td>
          <td>This can be found <strong><em>inside the Tentalus Playhouse.</em></strong></td>
        </tr>
        <tr>
          <td><Checkbox id="t-2-11" /></td>
          <td>993 Gil</td>
          <td><strong><span class="text-category-treasure-chest">Treasure Chest</span></strong></td>
          <td>This can be found <strong><em>inside the Tentalus Playhouse.</em></strong></td>
        </tr>
        <tr>
          <td><Checkbox id="t-2-12" /></td>
          <td>3,000 Gil</td>
          <td><strong><span class="text-category-story-reward">Story/Reward</span></strong></td>
          <td>This is given to you by Cid via story progression.</td>
        </tr>
      </tbody>
    </table>
  </div>

  <h3 class="text-2xl">Summit Station (<span class="text-error">Discs 2 and 3 Only</span>)</h3>

  <div class="rounded-box border-base-content/5 bg-base-100 overflow-x-auto border">
    <table class="table-xs table">
      <colgroup>
        <col style="width: 5%" />
        <col style="width: 20%" />
        <col style="width: 20%" />
        <col style="width: 55%" />
      </colgroup>
      <thead>
        <tr>
          <th></th>
          <th>Item</th>
          <th>Category</th>
          <th>Location</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td><Checkbox id="t-2-13" /></td>
          <td>
            <div>Phoenix Down</div>
          </td>
          <td>
            <div>
              <strong><span class="text-category-treasure-chest">Treasure Chest</span></strong>
            </div>
          </td>
          <td>
            <div>This can be found to the left of the receptionist's desk in the Station.</div>
          </td>
        </tr>
      </tbody>
    </table>
  </div>

  <h3 class="text-2xl">Treno (<span class="text-error">Disc 2 Only</span>)</h3>

  <div class="rounded-box border-base-content/5 bg-base-100 overflow-x-auto border">
    <table class="table-xs table">
      <colgroup>
        <col style="width: 5%" />
        <col style="width: 20%" />
        <col style="width: 20%" />
        <col style="width: 55%" />
      </colgroup>
      <thead>
        <tr>
          <th></th>
          <th>Item</th>
          <th>Category</th>
          <th>Location</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td><Checkbox id="t-2-14" /></td>
          <td>Tonberry Tetra Card</td>
          <td><strong><span class="text-category-story-reward">Story/Reward</span></strong></td>
          <td>
            This is awarded to you by <strong
              ><em>defeating the Griffin inside the Treno Weapon Shop</em></strong
            >.
          </td>
        </tr>
      </tbody>
    </table>
  </div>

  <h3 class="text-2xl">Treno (Discs 2, 3, and 4)</h3>

  <div class="rounded-box border-base-content/5 bg-base-100 overflow-x-auto border">
    <table class="table-xs table">
      <colgroup>
        <col style="width: 5%" />
        <col style="width: 20%" />
        <col style="width: 20%" />
        <col style="width: 55%" />
      </colgroup>
      <thead>
        <tr>
          <th></th>
          <th>Item</th>
          <th>Category</th>
          <th>Location</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td><Checkbox id="t-2-15" /></td>
          <td>1,000 Gil</td>
          <td><strong><span class="text-category-story-reward">Story/Reward</span></strong></td>
          <td>
            This is awarded from Queen Stella after giving her 1 Stellazio Coin.
            <div><br /></div>
            For more information, refer to<img
              alt="Bronze"
              title="Bronze"
              src="https://psnprofiles.com/lib/img/icons/buttons/bronze.png"
              class="input fr-fic fr-dii"
            />&nbsp;<a
              href="https://psnprofiles.com/guide/7421-final-fantasy-ix-trophy-guide#23-whats-your-sign"
              target="_blank"
              rel="noreferrer noopener">What's Your Sign?</a
            >
          </td>
        </tr>
        <tr>
          <td><Checkbox id="t-2-16" /></td>
          <td>Phoenix Pinion</td>
          <td><strong><span class="text-category-story-reward">Story/Reward</span></strong></td>
          <td>
            This is awarded from Queen Stella after giving her 2 Stellazio Coins.
            <div><br /></div>
            For more information, refer to<img
              alt="Bronze"
              title="Bronze"
              src="https://psnprofiles.com/lib/img/icons/buttons/bronze.png"
              class="input fr-fic fr-dii"
            />&nbsp;<a
              href="https://psnprofiles.com/guide/7421-final-fantasy-ix-trophy-guide#23-whats-your-sign"
              target="_blank"
              rel="noreferrer noopener">What's Your Sign?</a
            >
          </td>
        </tr>
        <tr>
          <td><Checkbox id="t-2-17" /></td>
          <td>2,000 Gil</td>
          <td><strong><span class="text-category-story-reward">Story/Reward</span></strong></td>
          <td>
            This is awarded from Queen Stella after giving her 3 Stellazio Coins.
            <div><br /></div>
            For more information, refer to<img
              alt="Bronze"
              title="Bronze"
              src="https://psnprofiles.com/lib/img/icons/buttons/bronze.png"
              class="input fr-fic fr-dii"
            />&nbsp;<a
              href="https://psnprofiles.com/guide/7421-final-fantasy-ix-trophy-guide#23-whats-your-sign"
              target="_blank"
              rel="noreferrer noopener">What's Your Sign?</a
            >
          </td>
        </tr>
        <tr>
          <td><Checkbox id="t-2-18" /></td>
          <td>Blood Sword</td>
          <td><strong><span class="text-category-story-reward">Story/Reward</span></strong></td>
          <td>
            This is awarded from Queen Stella after giving her 4 Stellazio Coins.
            <div><br /></div>
            For more information, refer to<img
              alt="Bronze"
              title="Bronze"
              src="https://psnprofiles.com/lib/img/icons/buttons/bronze.png"
              class="input fr-fic fr-dii"
            />&nbsp;<a
              href="https://psnprofiles.com/guide/7421-final-fantasy-ix-trophy-guide#23-whats-your-sign"
              target="_blank"
              rel="noreferrer noopener">What's Your Sign?</a
            >
          </td>
        </tr>
        <tr>
          <td><Checkbox id="t-2-19" /></td>
          <td>5,000 Gil</td>
          <td><strong><span class="text-category-story-reward">Story/Reward</span></strong></td>
          <td>
            This is awarded from Queen Stella after giving her 5 Stellazio Coins.
            <div><br /></div>
            For more information, refer to<img
              alt="Bronze"
              title="Bronze"
              src="https://psnprofiles.com/lib/img/icons/buttons/bronze.png"
              class="input fr-fic fr-dii"
            />&nbsp;<a
              href="https://psnprofiles.com/guide/7421-final-fantasy-ix-trophy-guide#23-whats-your-sign"
              target="_blank"
              rel="noreferrer noopener">What's Your Sign?</a
            >
          </td>
        </tr>
        <tr>
          <td><Checkbox id="t-2-20" /></td>
          <td>Elixir</td>
          <td><strong><span class="text-category-story-reward">Story/Reward</span></strong></td>
          <td>
            This is awarded from Queen Stella after giving her 6 Stellazio Coins.
            <div><br /></div>
            For more information, refer to<img
              alt="Bronze"
              title="Bronze"
              src="https://psnprofiles.com/lib/img/icons/buttons/bronze.png"
              class="input fr-fic fr-dii"
            />&nbsp;<a
              href="https://psnprofiles.com/guide/7421-final-fantasy-ix-trophy-guide#23-whats-your-sign"
              target="_blank"
              rel="noreferrer noopener">What's Your Sign?</a
            >
          </td>
        </tr>
        <tr>
          <td><Checkbox id="t-2-21" /></td>
          <td>10,000 Gil</td>
          <td><strong><span class="text-category-story-reward">Story/Reward</span></strong></td>
          <td>
            This is awarded from Queen Stella after giving her 7 Stellazio Coins.
            <div><br /></div>
            For more information, refer to<img
              alt="Bronze"
              title="Bronze"
              src="https://psnprofiles.com/lib/img/icons/buttons/bronze.png"
              class="input fr-fic fr-dii"
            />&nbsp;<a
              href="https://psnprofiles.com/guide/7421-final-fantasy-ix-trophy-guide#23-whats-your-sign"
              target="_blank"
              rel="noreferrer noopener">What's Your Sign?</a
            >
          </td>
        </tr>
        <tr>
          <td><Checkbox id="t-2-22" /></td>
          <td>Ether</td>
          <td><strong><span class="text-category-field-icon">Field Icon</span></strong></td>
          <td>
            This can be found to the <strong><em>left of Queen Stella's palace</em></strong> near the
            trees.
          </td>
        </tr>
        <tr>
          <td><Checkbox id="t-2-23" /></td>
          <td>Mythril Dagger</td>
          <td><strong><span class="text-category-treasure-chest">Treasure Chest</span></strong></td>
          <td>
            This can be found to the<strong><em>&nbsp;left of Doctor Tot's</em></strong> tower entrance.
          </td>
        </tr>
        <tr>
          <td><Checkbox id="t-2-24" /></td>
          <td>Yeti Tetra Card</td>
          <td><strong><span class="text-category-treasure-chest">Treasure Chest</span></strong></td>
          <td>
            This can be found to the <strong><em>left of the Treno Item Shop</em></strong> that's located
            in the Slums.
          </td>
        </tr>
        <tr>
          <td><Checkbox id="t-2-25" /></td>
          <td>Mini-Cid</td>
          <td><strong><span class="text-category-story-reward">Story/Reward</span></strong></td>
          <td>You are awarded this by winning this item at the Treno Auction House.</td>
        </tr>
        <tr>
          <td><Checkbox id="t-2-26" /></td>
          <td>Griffin's Heart</td>
          <td><strong><span class="text-category-story-reward">Story/Reward</span></strong></td>
          <td>You are awarded this by winning this item at the Treno Auction House.</td>
        </tr>
        <tr>
          <td><Checkbox id="t-2-27" /></td>
          <td>Une's Mirror</td>
          <td><strong><span class="text-category-story-reward">Story/Reward</span></strong></td>
          <td>You are awarded this by winning this item at the Treno Auction House.</td>
        </tr>
        <tr>
          <td><Checkbox id="t-2-28" /></td>
          <td>Doga's Artifact</td>
          <td><strong><span class="text-category-story-reward">Story/Reward</span></strong></td>
          <td>You are awarded this by winning this item at the Treno Auction House.</td>
        </tr>
        <tr>
          <td><Checkbox id="t-2-29" /></td>
          <td>Rat Tail</td>
          <td><strong><span class="text-category-story-reward">Story/Reward</span></strong></td>
          <td>You are awarded this by winning this item at the Treno Auction House.</td>
        </tr>
        <tr>
          <td><Checkbox id="t-2-30" /></td>
          <td>Taurus (Stellazio)</td>
          <td><strong><span class="text-category-field-icon">Field Icon</span></strong></td>
          <td>
            From the entrance of Treno, head one screen to the right. In that area, head down the
            ladder and you will find yourself at an item shop. Go behind the upper-right corner of
            the stand and the sign will be located there.
          </td>
        </tr>
        <tr>
          <td><Checkbox id="t-2-31" /></td>
          <td>Gemini (Stellazio)</td>
          <td><strong><span class="text-category-story-reward">Story/Reward</span></strong></td>
          <td>
            At the entrance, you will find a fountain on the left side of the screen. If you go up
            to it, you will have the choice to throw in 10 Gil. Throw 10 Gil into said fountain
            numerous times in-a-row until you are given the sign.
          </td>
        </tr>
        <tr>
          <td><Checkbox id="t-2-32" /></td>
          <td>1 Gil</td>
          <td><strong><span class="text-category-treasure-chest">Treasure Chest</span></strong></td>
          <td>
            This can be found to the <strong><em>right of the Treno Item Shop</em></strong> in the Slums.
          </td>
        </tr>
        <tr>
          <td><Checkbox id="t-2-33" /></td>
          <td>2,225 Gil</td>
          <td><strong><span class="text-category-field-icon">Field Icon</span></strong></td>
          <td>
            This can be found to the <strong
              ><em>left of the Treno Auction House's entrance.</em></strong
            >
          </td>
        </tr>
      </tbody>
    </table>
  </div>

  <h3 class="text-2xl">Gargan Roo (Disc 2)</h3>

  <div class="rounded-box border-base-content/5 bg-base-100 overflow-x-auto border">
    <table class="table-xs table">
      <colgroup>
        <col style="width: 5%" />
        <col style="width: 20%" />
        <col style="width: 20%" />
        <col style="width: 55%" />
      </colgroup>
      <thead>
        <tr>
          <th></th>
          <th>Item</th>
          <th>Category</th>
          <th>Location</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td><Checkbox id="t-2-34" /></td>
          <td>Phoenix Down</td>
          <td><strong><span class="text-category-treasure-chest">Treasure Chest</span></strong></td>
          <td>
            This can be found to the left of the lever that resides on the leftmost platform.
          </td>
        </tr>
        <tr>
          <td><Checkbox id="t-2-35" /></td>
          <td>Chain Plate</td>
          <td><strong><span class="text-category-treasure-chest">Treasure Chest</span></strong></td>
          <td>
            This can be found to the right of the entryway that leads to the leftmost platform.
          </td>
        </tr>
      </tbody>
    </table>
  </div>

  <div class="flex flex-col gap-4">
    <h3 class="text-2xl">Cleyra's Trunk (<span class="text-error">Disc 2 Only</span>)</h3>
    <div class="alert alert-error">
      This location/area will be "locked away" later on in the game due to story progression. It's
      best to get most if not all Items/Treasures here if possible before moving on too far.
    </div>
  </div>

  <div class="rounded-box border-base-content/5 bg-base-100 overflow-x-auto border">
    <table class="table-xs table">
      <colgroup>
        <col style="width: 5%" />
        <col style="width: 20%" />
        <col style="width: 20%" />
        <col style="width: 55%" />
      </colgroup>
      <thead>
        <tr>
          <th></th>
          <th>Item</th>
          <th>Category</th>
          <th>Location</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td><Checkbox id="t-2-36" /></td>
          <td>Potion</td>
          <td><strong><span class="text-category-treasure-chest">Treasure Chest</span></strong></td>
          <td>
            <div>
              This can be found <strong><em>near the top of the Tree Trunk</em></strong> at the fork
              in the road.
            </div>
          </td>
        </tr>
        <tr>
          <td><Checkbox id="t-2-37" /></td>
          <td>Hi-Potion</td>
          <td><strong><span class="text-category-treasure-chest">Treasure Chest</span></strong></td>
          <td>
            <div>
              This can be found in the area that has the <strong
                ><em>two quicksand holes</em></strong
              >.
            </div>
          </td>
        </tr>
        <tr>
          <td><Checkbox id="t-2-38" /></td>
          <td>Ether</td>
          <td><strong><span class="text-category-treasure-chest">Treasure Chest</span></strong></td>
          <td>
            <div>
              This can be found in the area that has the<strong
                ><em>&nbsp;interactable switch that changes the sand's flow</em></strong
              >.
            </div>
          </td>
        </tr>
        <tr>
          <td><Checkbox id="t-2-39" /></td>
          <td>Elixir</td>
          <td><strong><span class="text-category-treasure-chest">Treasure Chest</span></strong></td>
          <td>
            <div>
              This can be found on the righthand side of the fork in the road. The same path with
              the lever that you need to pull to change the sand's level.
            </div>
          </td>
        </tr>
        <tr>
          <td><Checkbox id="t-2-40" /></td>
          <td>Phoenix Down</td>
          <td><strong><span class="text-category-treasure-chest">Treasure Chest</span></strong></td>
          <td>
            <div>
              This can be found in the<strong><em>&nbsp;first area</em></strong> of the Trunk.
            </div>
          </td>
        </tr>
        <tr>
          <td><Checkbox id="t-2-41" /></td>
          <td>Remedy</td>
          <td><strong><span class="text-category-treasure-chest">Treasure Chest</span></strong></td>
          <td>
            <div>
              This can be found in the area <strong><em>after you cross the bridge</em></strong>.
            </div>
          </td>
        </tr>
        <tr>
          <td><Checkbox id="t-2-42" /></td>
          <td>Gysahl Greens</td>
          <td><strong><span class="text-category-treasure-chest">Treasure Chest</span></strong></td>
          <td>
            <div>
              This can be found <strong><em>behind the ladder</em></strong> that leads you to the Cleyra
              Town area.
            </div>
          </td>
        </tr>
        <tr>
          <td><Checkbox id="t-2-43" /></td>
          <td>Tent</td>
          <td><strong><span class="text-category-treasure-chest">Treasure Chest</span></strong></td>
          <td>
            <div>
              This can be found in the <strong
                ><em>same area that Monev the Moogle is found in</em></strong
              >.
            </div>
          </td>
        </tr>
        <tr>
          <td><Checkbox id="t-2-44" /></td>
          <td>Flame Staff</td>
          <td><strong><span class="text-category-treasure-chest">Treasure Chest</span></strong></td>
          <td>
            <div>
              This can be found<strong><em>&nbsp;to the left of the forking path</em></strong> that leads
              to the Bridge.
            </div>
          </td>
        </tr>
        <tr>
          <td><Checkbox id="t-2-45" /></td>
          <td>Ice Staff</td>
          <td><strong><span class="text-category-treasure-chest">Treasure Chest</span></strong></td>
          <td>
            <div>
              This can be found <strong
                ><em>behind the lone Tree in the area where the sand's level is changed</em></strong
              > (this can only be obtained before the sand's level is altered).
            </div>
          </td>
        </tr>
        <tr>
          <td><Checkbox id="t-2-46" /></td>
          <td>Needle Fork</td>
          <td><strong><span class="text-category-treasure-chest">Treasure Chest</span></strong></td>
          <td>
            <div>
              This can be found in the <strong
                ><em>same area that Monev the Moogle is found in</em></strong
              >.
            </div>
          </td>
        </tr>
        <tr>
          <td><Checkbox id="t-2-47" /></td>
          <td>Mythril Gloves</td>
          <td><strong><span class="text-category-treasure-chest">Treasure Chest</span></strong></td>
          <td>
            <div>
              This can be found on the <strong
                ><em>same path that leads to the switch that you use to alter the sand's level</em
                ></strong
              >.
            </div>
          </td>
        </tr>
        <tr>
          <td><Checkbox id="t-2-48" /></td>
          <td>Mythril Vest</td>
          <td><strong><span class="text-category-treasure-chest">Treasure Chest</span></strong></td>
          <td>
            <div>
              This can be found <strong
                ><em
                  >inside the left-side tunnel that resides in the room with the three different
                  tunnel entrances</em
                ></strong
              >.
            </div>
          </td>
        </tr>
        <tr>
          <td><Checkbox id="t-2-49" /></td>
          <td>Silk Robe</td>
          <td><strong><span class="text-category-treasure-chest">Treasure Chest</span></strong></td>
          <td>
            <div>
              This can be found in the room<strong
                ><em>&nbsp;that is filled with sand after the sand's level has been altered</em
                ></strong
              >.
            </div>
          </td>
        </tr>
        <tr>
          <td><Checkbox id="t-2-50" /></td>
          <td>Desert Boots</td>
          <td><strong><span class="text-category-treasure-chest">Treasure Chest</span></strong></td>
          <td>
            <div>
              This can be found<strong
                ><em
                  >&nbsp;behind one of the pillars in the room that has the three different tunnel
                  entrances</em
                ></strong
              >.
            </div>
          </td>
        </tr>
        <tr>
          <td><Checkbox id="t-2-51" /></td>
          <td>Magician Shoes</td>
          <td><strong><span class="text-category-treasure-chest">Treasure Chest</span></strong></td>
          <td>
            <div>
              This can be found in <strong><em>the room that has the lone tree</em></strong> (this can
              only be obtained before the sand's level is altered).
            </div>
          </td>
        </tr>
        <tr>
          <td><Checkbox id="t-2-52" /></td>
          <td>900 Gil</td>
          <td><strong><span class="text-category-treasure-chest">Treasure Chest</span></strong></td>
          <td>
            <div>
              This can be found in the <strong><em>same room that has the quicksand</em></strong>.
            </div>
          </td>
        </tr>
      </tbody>
    </table>
  </div>

  <div class="flex flex-col gap-4">
    <h3 class="text-2xl">Cleyra Settlement (<span class="text-error">Disc 2 Only</span>)</h3>
    <div class="alert alert-error">
      This location/area will be "locked away" later on in the game due to story progression. It's
      best to get most if not all Items/Treasures here if possible before moving on too far.
    </div>
  </div>

  <div class="rounded-box border-base-content/5 bg-base-100 overflow-x-auto border">
    <table class="table-xs table">
      <colgroup>
        <col style="width: 5%" />
        <col style="width: 20%" />
        <col style="width: 20%" />
        <col style="width: 55%" />
      </colgroup>
      <thead>
        <tr>
          <th></th>
          <th>Item</th>
          <th>Category</th>
          <th>Location</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td><Checkbox id="t-2-53" /></td>
          <td>Ether</td>
          <td><strong><span class="text-category-field-icon">Field Icon</span></strong></td>
          <td>
            This can be found<strong><em>&nbsp;inside the Inn on the upper floor</em></strong>
            sitting on a nightstand.
          </td>
        </tr>
        <tr>
          <td><Checkbox id="t-2-54" /></td>
          <td>Ether</td>
          <td><strong><span class="text-category-field-icon">Field Icon</span></strong></td>
          <td>
            This can be found in the<strong><em>&nbsp;balcony of the Cathedral</em></strong>.
          </td>
        </tr>
        <tr>
          <td><Checkbox id="t-2-55" /></td>
          <td>Echo Screen</td>
          <td><strong><span class="text-category-field-icon">Field Icon</span></strong></td>
          <td>
            This can be found to the just <strong
              ><em>outside of the Cathedral to the right</em></strong
            >.
          </td>
        </tr>
        <tr>
          <td><Checkbox id="t-2-56" /></td>
          <td>Echo Screen</td>
          <td><strong><span class="text-category-field-icon">Field Icon</span></strong></td>
          <td>
            This can be found <strong><em>inside the Inn near the cash register</em></strong>.
          </td>
        </tr>
        <tr>
          <td><Checkbox id="t-2-57" /></td>
          <td>Remedy</td>
          <td><strong><span class="text-category-field-icon">Field Icon</span></strong></td>
          <td>
            This can be found just <strong
              ><em>outside of the Inn on the set of steps to the right</em></strong
            >.
          </td>
        </tr>
        <tr>
          <td><Checkbox id="t-2-58" /></td>
          <td>Phoenix Pinion</td>
          <td><strong><span class="text-category-field-icon">Field Icon</span></strong></td>
          <td>
            This can be found in the area that has<strong
              ><em>&nbsp;the fork in the path that splits into three different pathways</em></strong
            >.
          </td>
        </tr>
        <tr>
          <td><Checkbox id="t-2-59" /></td>
          <td>Phoenix Pinion</td>
          <td><strong><span class="text-category-field-icon">Field Icon</span></strong></td>
          <td>
            This can be found in the <strong
              ><em>first area on a ledge that faces the entrance to the Settlement</em></strong
            >.
          </td>
        </tr>
        <tr>
          <td><Checkbox id="t-2-60" /></td>
          <td>Phoenix Pinion</td>
          <td><strong><span class="text-category-field-icon">Field Icon</span></strong></td>
          <td>
            This can be found <strong><em>inside the Cathedral behind the harp</em></strong>.
          </td>
        </tr>
        <tr>
          <td><Checkbox id="t-2-61" /></td>
          <td>Gysahl Greens</td>
          <td><strong><span class="text-category-field-icon">Field Icon</span></strong></td>
          <td>
            This can be found <strong><em>outside of the Cathedral to the right</em></strong>.
          </td>
        </tr>
        <tr>
          <td><Checkbox id="t-2-62" /></td>
          <td>Thunder Gloves</td>
          <td><strong><span class="text-category-field-icon">Field Icon</span></strong></td>
          <td>
            This can be found <strong
              ><em>in the area that has the clock and the waterfall</em></strong
            >. It's located <strong><em>behind the aforementioned clock</em></strong>.
          </td>
        </tr>
        <tr>
          <td><Checkbox id="t-2-63" /></td>
          <td>Yellow Scarf</td>
          <td><strong><span class="text-category-field-icon">Field Icon</span></strong></td>
          <td>
            This can be found<strong
              ><em>&nbsp;inside the Cathedral to the left of the entrance</em></strong
            >.
          </td>
        </tr>
        <tr>
          <td><Checkbox id="t-2-64" /></td>
          <td>Ore</td>
          <td><strong><span class="text-category-field-icon">Field Icon</span></strong></td>
          <td>
            This can be found in the<strong><em>&nbsp;same area as the Inn</em></strong>. It's in
            the <strong><em>far bottom-right corner of the area</em></strong>.
          </td>
        </tr>
        <tr>
          <td><Checkbox id="t-2-65" /></td>
          <td>Ore</td>
          <td><strong><span class="text-category-field-icon">Field Icon</span></strong></td>
          <td>
            This can be found <strong><em>inside the Cathedral on the podium</em></strong>.
          </td>
        </tr>
        <tr>
          <td><Checkbox id="t-2-66" /></td>
          <td>970 Gil</td>
          <td><strong><span class="text-category-field-icon">Field Icon</span></strong></td>
          <td>
            This is found inside Antlion's pit. Antlion is a mini-boss that you fight inside Cleyra.
          </td>
        </tr>
        <tr>
          <td><Checkbox id="t-2-67" /></td>
          <td>1,250 Gil</td>
          <td><strong><span class="text-category-field-icon">Field Icon</span></strong></td>
          <td>
            This can be found <strong
              ><em>inside the Inn to the right of the cash register</em></strong
            >.
          </td>
        </tr>
        <tr>
          <td><Checkbox id="t-2-68" /></td>
          <td>Emerald</td>
          <td><strong><span class="text-category-story-reward">Story/Reward</span></strong></td>
          <td>This is given to Freya from the High Priest of Cleyra.&nbsp;</td>
        </tr>
        <tr>
          <td><Checkbox id="t-2-69" /></td>
          <td>Ether</td>
          <td><strong><span class="text-category-story-reward">Story/Reward</span></strong></td>
          <td>
            This is awarded after talking to one of the surviving residents of Cleyra after
            escorting them to safety.<br /><br />You will want to do this for the missable trophy
            <img
              alt="Bronze"
              title="Bronze"
              src="https://psnprofiles.com/lib/img/icons/buttons/bronze.png"
              class="input fr-fic fr-dii"
            />&nbsp;<a
              href="https://psnprofiles.com/guide/7421-final-fantasy-ix-trophy-guide#55-out-of-harms-way"
              target="_blank"
              rel="noreferrer noopener">Out of Harm's Way</a
            >. Refer to the trophy for more information.
          </td>
        </tr>
        <tr>
          <td><Checkbox id="t-2-70" /></td>
          <td>Elixir</td>
          <td><strong><span class="text-category-story-reward">Story/Reward</span></strong></td>
          <td>
            This is awarded after talking to one of the surviving residents of Cleyra after
            escorting them to safety.<br /><br />You will want to do this for the missable trophy
            <img
              alt="Bronze"
              title="Bronze"
              src="https://psnprofiles.com/lib/img/icons/buttons/bronze.png"
              class="input fr-fic fr-dii"
            />&nbsp;<a
              href="https://psnprofiles.com/guide/7421-final-fantasy-ix-trophy-guide#55-out-of-harms-way"
              target="_blank"
              rel="noreferrer noopener">Out of Harm's Way</a
            >. Refer to the trophy for more information.
          </td>
        </tr>
        <tr>
          <td><Checkbox id="t-2-71" /></td>
          <td>Phoenix Down</td>
          <td><strong><span class="text-category-story-reward">Story/Reward</span></strong></td>
          <td>
            This is awarded after talking to one of the surviving residents of Cleyra after
            escorting them to safety.<br /><br />You will want to do this for the missable trophy
            <img
              alt="Bronze"
              title="Bronze"
              src="https://psnprofiles.com/lib/img/icons/buttons/bronze.png"
              class="input fr-fic fr-dii"
            />&nbsp;<a
              href="https://psnprofiles.com/guide/7421-final-fantasy-ix-trophy-guide#55-out-of-harms-way"
              target="_blank"
              rel="noreferrer noopener">Out of Harm's Way</a
            >. Refer to the trophy for more information.
          </td>
        </tr>
        <tr>
          <td><Checkbox id="t-2-72" /></td>
          <td>Remedy</td>
          <td><strong><span class="text-category-story-reward">Story/Reward</span></strong></td>
          <td>
            This is awarded after talking to one of the surviving residents of Cleyra after
            escorting them to safety.<br /><br />You will want to do this for the missable trophy
            <img
              alt="Bronze"
              title="Bronze"
              src="https://psnprofiles.com/lib/img/icons/buttons/bronze.png"
              class="input fr-fic fr-dii"
            />&nbsp;<a
              href="https://psnprofiles.com/guide/7421-final-fantasy-ix-trophy-guide#55-out-of-harms-way"
              target="_blank"
              rel="noreferrer noopener">Out of Harm's Way</a
            >. Refer to the trophy for more information.
          </td>
        </tr>
        <tr>
          <td><Checkbox id="t-2-73" /></td>
          <td>Phoenix Pinion</td>
          <td><strong><span class="text-category-story-reward">Story/Reward</span></strong></td>
          <td>
            This is awarded after talking to one of the surviving residents of Cleyra after
            escorting them to safety.<br /><br />You will want to do this for the missable trophy
            <img
              alt="Bronze"
              title="Bronze"
              src="https://psnprofiles.com/lib/img/icons/buttons/bronze.png"
              class="input fr-fic fr-dii"
            />&nbsp;<a
              href="https://psnprofiles.com/guide/7421-final-fantasy-ix-trophy-guide#55-out-of-harms-way"
              target="_blank"
              rel="noreferrer noopener">Out of Harm's Way</a
            >. Refer to the trophy for more information.
          </td>
        </tr>
        <tr>
          <td><Checkbox id="t-2-74" /></td>
          <td>Nymph Tetra Card</td>
          <td><strong><span class="text-category-story-reward">Story/Reward</span></strong></td>
          <td>
            This is awarded after talking to one of the surviving residents of Cleyra after
            escorting them to safety.<br /><br />You will want to do this for the missable trophy
            <img
              alt="Bronze"
              title="Bronze"
              src="https://psnprofiles.com/lib/img/icons/buttons/bronze.png"
              class="input fr-fic fr-dii"
            />&nbsp;<a
              href="https://psnprofiles.com/guide/7421-final-fantasy-ix-trophy-guide#55-out-of-harms-way"
              target="_blank"
              rel="noreferrer noopener">Out of Harm's Way</a
            >. Refer to the trophy for more information.
          </td>
        </tr>
        <tr>
          <td><Checkbox id="t-2-75" /></td>
          <td>Zuu Tetra Card</td>
          <td><strong><span class="text-category-story-reward">Story/Reward</span></strong></td>
          <td>
            This is awarded after talking to one of the surviving residents of Cleyra after
            escorting them to safety.<br /><br />You will want to do this for the missable trophy
            <img
              alt="Bronze"
              title="Bronze"
              src="https://psnprofiles.com/lib/img/icons/buttons/bronze.png"
              class="input fr-fic fr-dii"
            />&nbsp;<a
              href="https://psnprofiles.com/guide/7421-final-fantasy-ix-trophy-guide#55-out-of-harms-way"
              target="_blank"
              rel="noreferrer noopener">Out of Harm's Way</a
            >. Refer to the trophy for more information.
          </td>
        </tr>
      </tbody>
    </table>
  </div>

  <div class="flex flex-col gap-4">
    <h3 class="text-2xl">Pinnacle Rocks (<span class="text-error">Disc 2 Only</span>)</h3>
    <div class="alert alert-error">
      This location/area will be "locked away" later on in the game due to story progression. It's
      best to get most if not all Items/Treasures here if possible before moving on too far.
    </div>
  </div>

  <div class="rounded-box border-base-content/5 bg-base-100 overflow-x-auto border">
    <table class="table-xs table">
      <colgroup>
        <col style="width: 5%" />
        <col style="width: 20%" />
        <col style="width: 20%" />
        <col style="width: 55%" />
      </colgroup>
      <thead>
        <tr>
          <th></th>
          <th>Item</th>
          <th>Category</th>
          <th>Location</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td><Checkbox id="t-2-76" /></td>
          <td>Elixir</td>
          <td><strong><span class="text-category-treasure-chest">Treasure Chest</span></strong></td>
          <td>
            This can be found at the<strong><em>&nbsp;very end of the first area</em></strong>.
          </td>
        </tr>
        <tr>
          <td><Checkbox id="t-2-77" /></td>
          <td>Phoenix Down</td>
          <td><strong><span class="text-category-treasure-chest">Treasure Chest</span></strong></td>
          <td>
            This can be found at the<strong><em>&nbsp;very end of the first area</em></strong>.
          </td>
        </tr>
        <tr>
          <td><Checkbox id="t-2-78" /></td>
          <td>The Ogre</td>
          <td><strong><span class="text-category-treasure-chest">Treasure Chest</span></strong></td>
          <td>
            In the<strong><em>&nbsp;area with the elevated branching path</em></strong>, this can be
            found to the left of the aforementioned branch.
          </td>
        </tr>
        <tr>
          <td><Checkbox id="t-2-79" /></td>
          <td>Mythril Armlet</td>
          <td><strong><span class="text-category-treasure-chest">Treasure Chest</span></strong></td>
          <td>
            In the<strong><em>&nbsp;area with the elevated branching path</em></strong>, this can be
            found on the ground when you jump off of one of the paths.
          </td>
        </tr>
        <tr>
          <td><Checkbox id="t-2-80" /></td>
          <td>Mythril Vest</td>
          <td><strong><span class="text-category-treasure-chest">Treasure Chest</span></strong></td>
          <td>
            This can be found in the <strong
              ><em>same area where Monty the Moogle is located</em></strong
            >.
          </td>
        </tr>
        <tr>
          <td><Checkbox id="t-2-81" /></td>
          <td>Peridot</td>
          <td><strong><span class="text-category-story-reward">Story/Reward</span></strong></td>
          <td>
            This is awarded to you once you have pieced together the Hero Story at Ramuh's request.
          </td>
        </tr>
      </tbody>
    </table>
  </div>

  <div class="flex flex-col gap-4">
    <h3 class="text-2xl">Fossil Roo (<span class="text-error">Disc 2 Only</span>)</h3>
    <div class="alert alert-error">
      This location/area will be "locked away" later on in the game due to story progression. It's
      best to get most if not all Items/Treasures here if possible before moving on too far.
    </div>
  </div>

  <div class="rounded-box border-base-content/5 bg-base-100 overflow-x-auto border">
    <table class="table-xs table">
      <colgroup>
        <col style="width: 5%" />
        <col style="width: 20%" />
        <col style="width: 20%" />
        <col style="width: 55%" />
      </colgroup>
      <thead>
        <tr>
          <th></th>
          <th>Item</th>
          <th>Category</th>
          <th>Location</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td><Checkbox id="t-2-82" /></td>
          <td>Ether</td>
          <td><strong><span class="text-category-treasure-chest">Treasure Chest</span></strong></td>
          <td>
            This can be found <strong
              ><em>above the pathway that takes you to the 2nd Gargant Route Switch</em></strong
            >.
          </td>
        </tr>
        <tr>
          <td><Checkbox id="t-2-83" /></td>
          <td>Elixir</td>
          <td><strong><span class="text-category-field-icon">Field Icon</span></strong></td>
          <td>This can be found <strong><em>inside Armodullahan's cage</em></strong>.</td>
        </tr>
        <tr>
          <td><Checkbox id="t-2-84" /></td>
          <td>Lamia's Tiara</td>
          <td><strong><span class="text-category-treasure-chest">Treasure Chest</span></strong></td>
          <td>
            This can be found in a <strong
              ><em>dead end that is accessed by toggling the 4th Gargant Route Switch</em></strong
            >.
          </td>
        </tr>
        <tr>
          <td><Checkbox id="t-2-85" /></td>
          <td>Survival Vest</td>
          <td><strong><span class="text-category-field-icon">Field Icon</span></strong></td>
          <td>
            This can be found on the <strong><em>far left of the Storage area</em></strong>.<br
            /></td
          >
        </tr>
        <tr>
          <td><Checkbox id="t-2-86" /></td>
          <td>Fairy Earrings</td>
          <td><strong><span class="text-category-treasure-chest">Treasure Chest</span></strong></td>
          <td>
            This can be found on a <strong
              ><em>path that is accessed by toggling the 2nd Gargant Route Switch</em></strong
            >.
          </td>
        </tr>
        <tr>
          <td><Checkbox id="t-2-87" /></td>
          <td>Madain's Ring</td>
          <td><strong><span class="text-category-field-icon">Field Icon</span></strong></td>
          <td>
            This can be found via the mining mini-game.<br /><br />You will want to get this for the
            missable trophy
            <img
              alt="Bronze"
              title="Bronze"
              src="https://psnprofiles.com/lib/img/icons/buttons/bronze.png"
              class="input fr-fic fr-dii"
            />&nbsp;<a
              href="https://psnprofiles.com/guide/7421-final-fantasy-ix-trophy-guide#32-the-one-ring"
              target="_blank"
              rel="noreferrer noopener">The One Ring</a
            >. For more information, refer to the trophy entry.
          </td>
        </tr>
      </tbody>
    </table>
  </div>

  <div class="flex flex-col gap-4">
    <h3 class="text-2xl">Conde Petie (<span class="text-error">Discs 2 and 3 Only</span>)</h3>
    <div class="alert alert-error">
      This location/area will be "locked away" later on in the game due to story progression. It's
      best to get most if not all Items/Treasures here if possible before moving on too far.
    </div>
  </div>

  <div class="rounded-box border-base-content/5 bg-base-100 overflow-x-auto border">
    <table class="table-xs table">
      <colgroup>
        <col style="width: 5%" />
        <col style="width: 20%" />
        <col style="width: 20%" />
        <col style="width: 55%" />
      </colgroup>
      <thead>
        <tr>
          <th></th>
          <th>Item</th>
          <th>Category</th>
          <th>Location</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td><Checkbox id="t-2-88" /></td>
          <td>
            <div>Phoenix Pinion</div>
          </td>
          <td>
            <div><strong><span class="text-category-field-icon">Field Icon</span></strong></div>
          </td>
          <td>
            <div>
              This can be found on the <strong
                ><em>set of stairs that lead to the Item Vendor&nbsp;shop</em></strong
              >.
            </div>
          </td>
        </tr>
        <tr>
          <td><Checkbox id="t-2-89" /></td>
          <td>Diamond</td>
          <td><strong><span class="text-category-field-icon">Field Icon</span></strong></td>
          <td>
            This can be found <strong><em>on the Kirkboat in the Shrine area</em></strong>.
          </td>
        </tr>
        <tr>
          <td><Checkbox id="t-2-90" /></td>
          <td>Oglop Tetra Card</td>
          <td><strong><span class="text-category-story-reward">Story/Reward</span></strong></td>
          <td>This is awarded to you by giving the boy inside the Item Vendor shop an Oglop. </td>
        </tr>
        <tr>
          <td><Checkbox id="t-2-91" /></td>
          <td>1,800 Gil</td>
          <td><strong><span class="text-category-field-icon">Field Icon</span></strong></td>
          <td>
            This can be found <strong><em>behind one of the beds inside the Inn</em></strong>.
          </td>
        </tr>
        <tr>
          <td><Checkbox id="t-2-92" /></td>
          <td>2,700 Gil</td>
          <td><strong><span class="text-category-field-icon">Field Icon</span></strong></td>
          <td>
            This can be found <strong><em>to the left of the entrance</em></strong> inside Conde Petie.
          </td>
        </tr>
      </tbody>
    </table>
  </div>

  <h3 class="text-2xl">Black Mage Village (Discs 2, 3, and 4)</h3>

  <div class="rounded-box border-base-content/5 bg-base-100 overflow-x-auto border">
    <table class="table-xs table">
      <colgroup>
        <col style="width: 5%" />
        <col style="width: 20%" />
        <col style="width: 20%" />
        <col style="width: 55%" />
      </colgroup>
      <thead>
        <tr>
          <th></th>
          <th>Item</th>
          <th>Category</th>
          <th>Location</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td><Checkbox id="t-2-93" /></td>
          <td>Ether</td>
          <td><strong><span class="text-category-field-icon">Field Icon</span></strong></td>
          <td>
            This can be found<strong
              ><em>&nbsp;inside the Item Vendor Shop to the left of the main counter</em></strong
            >.
          </td>
        </tr>
        <tr>
          <td><Checkbox id="t-2-94" /></td>
          <td>Elixir</td>
          <td><strong><span class="text-category-field-icon">Field Icon</span></strong></td>
          <td>
            This can be found to the <strong
              ><em>right of the entrance to the Weapon Shop Vendor</em></strong
            >.
          </td>
        </tr>
        <tr>
          <td><Checkbox id="t-2-95" /></td>
          <td>Gysahl Greens</td>
          <td><strong><span class="text-category-field-icon">Field Icon</span></strong></td>
          <td>
            This can be found<strong><em>&nbsp;inside the stable that has the Chocobo</em></strong>.
          </td>
        </tr>
        <tr>
          <td><Checkbox id="t-2-96" /></td>
          <td>Black Belt</td>
          <td><strong><span class="text-category-treasure-chest">Treasure Chest</span></strong></td>
          <td>
            This can be found in <strong><em>the second floor of the Item Vendor Shop</em></strong>.
          </td>
        </tr>
        <tr>
          <td><Checkbox id="t-2-97" /></td>
          <td>Virgo</td>
          <td><strong><span class="text-category-field-icon">Field Icon</span></strong></td>
          <td>This can be found <strong><em>in the room inside the Inn</em></strong>.</td>
        </tr>
        <tr>
          <td><Checkbox id="t-2-98" /></td>
          <td>843 Gil</td>
          <td><strong><span class="text-category-treasure-chest">Treasure Chest</span></strong></td>
          <td>
            This can be found <strong><em>on the rooftop of the Synthesis Shop</em></strong>.
          </td>
        </tr>
        <tr>
          <td><Checkbox id="t-2-99" /></td>
          <td>2,000 Gil</td>
          <td><strong><span class="text-category-treasure-chest">Treasure Chest</span></strong></td>
          <td>
            This can be found <strong><em>behind the counter inside the Synthesis Shop</em></strong
            >.
          </td>
        </tr>
      </tbody>
    </table>
  </div>

  <div class="flex flex-col gap-4">
    <h3 class="text-2xl">
      Conde Petie Mountain Path (<span class="text-error">Discs 2 and 3 Only</span>)
    </h3>
    <div class="alert alert-error">
      This location/area will be "locked away" later on in the game due to story progression. It's
      best to get most if not all Items/Treasures here if possible before moving on too far.
    </div>
  </div>

  <div class="rounded-box border-base-content/5 bg-base-100 overflow-x-auto border">
    <table class="table-xs table">
      <colgroup>
        <col style="width: 5%" />
        <col style="width: 20%" />
        <col style="width: 20%" />
        <col style="width: 55%" />
      </colgroup>
      <thead>
        <tr>
          <th></th>
          <th>Item</th>
          <th>Category</th>
          <th>Location</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td><Checkbox id="t-2-100" /></td>
          <td>Ether</td>
          <td><strong><span class="text-category-treasure-chest">Treasure Chest</span></strong></td>
          <td>
            This can be found to the <strong
              ><em>left of the statue that houses the Green Stone</em></strong
            >.
          </td>
        </tr>
        <tr>
          <td><Checkbox id="t-2-101" /></td>
          <td>Remedy</td>
          <td><strong><span class="text-category-treasure-chest">Treasure Chest</span></strong></td>
          <td>
            this can be found on <strong
              ><em>one of the ledges in the first area of Conde Petie Mountain Path</em></strong
            >.
          </td>
        </tr>
        <tr>
          <td><Checkbox id="t-2-102" /></td>
          <td>Tent</td>
          <td><strong><span class="text-category-treasure-chest">Treasure Chest</span></strong></td>
          <td>
            This can be found on <strong
              ><em>one of the ledges in the first area of Conde Petie Mountain Path</em></strong
            >.
          </td>
        </tr>
        <tr>
          <td><Checkbox id="t-2-103" /></td>
          <td>Moonstone</td>
          <td><strong><span class="text-category-story-reward">Story/Reward</span></strong></td>
          <td>
            This is awarded <strong
              ><em>after placing the Red, Blue, Yellow, and Green stones inside the altar</em
              ></strong
            >.<br /><br />This is one of the four Moonstones needed for the missable trophy
            <img
              alt="Gold"
              title="Gold"
              src="https://psnprofiles.com/lib/img/icons/buttons/gold.png"
              class="input fr-fic fr-dii"
            />&nbsp;<a
              href="https://psnprofiles.com/guide/7421-final-fantasy-ix-trophy-guide#42-over-the-moon"
              target="_blank"
              rel="noreferrer noopener">Over The Moon</a
            >. For more information, refer to the trophy entry.
          </td>
        </tr>
        <tr>
          <td><Checkbox id="t-2-104" /></td>
          <td>Red Stone</td>
          <td><strong><span class="text-category-field-icon">Field Icon</span></strong></td>
          <td>
            This can be found in a statue that's located <strong
              ><em>on the right-side ledge of the first area in Conde Petie Mountain Path</em
              ></strong
            >.
          </td>
        </tr>
        <tr>
          <td><Checkbox id="t-2-105" /></td>
          <td>Blue Stone</td>
          <td><strong><span class="text-category-field-icon">Field Icon</span></strong></td>
          <td>
            This can be found in a statue that's located on a <strong
              ><em>high ledge that you can get to via climbing a vine</em></strong
            >. Once you climb the aforementioned vine, then go right one screen and it'll be there.
          </td>
        </tr>
        <tr>
          <td><Checkbox id="t-2-106" /></td>
          <td>Yellow Stone</td>
          <td><strong><span class="text-category-field-icon">Field Icon</span></strong></td>
          <td>
            this can be found <strong
              ><em
                >in a statue that is located at a fork in the road that you get to after defeating
                Hilgigars</em
              ></strong
            >.
          </td>
        </tr>
        <tr>
          <td><Checkbox id="t-2-107" /></td>
          <td>Green Stone</td>
          <td><strong><span class="text-category-field-icon">Field Icon</span></strong></td>
          <td>
            This can be found in a statue that is located in the <strong
              ><em>final area on the lower end of the path</em></strong
            >.
          </td>
        </tr>
      </tbody>
    </table>
  </div>

  <h3 class="text-2xl">Madain Sari (Discs 2, 3, and 4)</h3>

  <div class="rounded-box border-base-content/5 bg-base-100 overflow-x-auto border">
    <table class="table-xs table">
      <colgroup>
        <col style="width: 5%" />
        <col style="width: 20%" />
        <col style="width: 20%" />
        <col style="width: 55%" />
      </colgroup>
      <thead>
        <tr>
          <th></th>
          <th>Item</th>
          <th>Category</th>
          <th>Location</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td><Checkbox id="t-2-108" /></td>
          <td>Elixir</td>
          <td><strong><span class="text-category-story-reward">Story/Reward</span></strong></td>
          <td>This is given to you by the Moogles inside Madain Sari.</td>
        </tr>
        <tr>
          <td><Checkbox id="t-2-109" /></td>
          <td>Phoenix Down</td>
          <td><strong><span class="text-category-treasure-chest">Treasure Chest</span></strong></td>
          <td>
            This can be found <strong><em>inside the room that's below Eiko's porch</em></strong>.
          </td>
        </tr>
        <tr>
          <td><Checkbox id="t-2-110" /></td>
          <td>Phoenix Pinion</td>
          <td><strong><span class="text-category-treasure-chest">Treasure Chest</span></strong></td>
          <td>
            This can be <strong><em>found inside Eiko's House behind the table</em></strong>.
          </td>
        </tr>
        <tr>
          <td><Checkbox id="t-2-111" /></td>
          <td>Tent</td>
          <td><strong><span class="text-category-treasure-chest">Treasure Chest</span></strong></td>
          <td>
            This can be found <strong
              ><em>behind the bench that is in the same area as the central fountain</em></strong
            >.
          </td>
        </tr>
        <tr>
          <td><Checkbox id="t-2-112" /></td>
          <td>ore</td>
          <td><strong><span class="text-category-treasure-chest">Treasure Chest</span></strong></td>
          <td>
            This can be found <strong><em>inside Eiko's House near the table</em></strong>.
          </td>
        </tr>
        <tr>
          <td><Checkbox id="t-2-113" /></td>
          <td>Exploda</td>
          <td><strong><span class="text-category-story-reward">Story/Reward</span></strong></td>
          <td>This is given to you by the Moogles inside Madain Sari.</td>
        </tr>
        <tr>
          <td><Checkbox id="t-2-114" /></td>
          <td>Survival Vest</td>
          <td><strong><span class="text-category-treasure-chest">Treasure Chest</span></strong></td>
          <td>
            This can be found <strong><em>inside the room that's below Eiko's porch</em></strong>.
          </td>
        </tr>
        <tr>
          <td><Checkbox id="t-2-115" /></td>
          <td>Kirman Coffee</td>
          <td><strong><span class="text-category-field-icon">Field Icon</span></strong></td>
          <td>
            Once you go inside Eiko's house, you will need to <strong
              ><em>head to the kitchen area</em></strong
            >. Once you're there, go in between the two tables on the left-hand side of the kitchen
            and it'll be there.
          </td>
        </tr>
        <tr>
          <td><Checkbox id="t-2-116" /></td>
          <td>Libra (Stellazio)</td>
          <td><strong><span class="text-category-field-icon">Field Icon</span></strong></td>
          <td>
            This can be found <strong><em>in the area with the Fountain</em></strong>. It can be
            found behind the aforementioned Fountain.
          </td>
        </tr>
      </tbody>
    </table>
  </div>

  <div class="flex flex-col gap-4">
    <h3 class="text-2xl">Iifa Tree (<span class="text-error">Disc 2 Only</span>)</h3>
    <div class="alert alert-error">
      This location/area will be "locked away" later on in the game due to story progression. It's
      best to get most if not all Items/Treasures here if possible before moving on too far.
    </div>
  </div>

  <div class="rounded-box border-base-content/5 bg-base-100 overflow-x-auto border">
    <table class="table-xs table">
      <colgroup>
        <col style="width: 5%" />
        <col style="width: 20%" />
        <col style="width: 20%" />
        <col style="width: 55%" />
      </colgroup>
      <thead>
        <tr>
          <th></th>
          <th>Item</th>
          <th>Category</th>
          <th>Location</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td><Checkbox id="t-2-117" /></td>
          <td>Hi-Potion</td>
          <td><strong><span class="text-category-treasure-chest">Treasure Chest</span></strong></td>
          <td>This can be found at <strong><em>the bottom of the second area</em></strong>. </td>
        </tr>
        <tr>
          <td><Checkbox id="t-2-118" /></td>
          <td>Ether</td>
          <td><strong><span class="text-category-treasure-chest">Treasure Chest</span></strong></td>
          <td>
            This can be found <strong
              ><em>off the main path to the right in the third area</em></strong
            >.
          </td>
        </tr>
        <tr>
          <td><Checkbox id="t-2-119" /></td>
          <td>Elixir</td>
          <td><strong><span class="text-category-treasure-chest">Treasure Chest</span></strong></td>
          <td>
            This can be found at the base of the set of stairs in the final area where you fight the
            boss Soulcage.
          </td>
        </tr>
        <tr>
          <td><Checkbox id="t-2-120" /></td>
          <td>Phoenix Down</td>
          <td><strong><span class="text-category-treasure-chest">Treasure Chest</span></strong></td>
          <td>
            This can be found <strong><em>by pressing a switch in the second area</em></strong>.
            Pressing the switch makes this appear off the main path.
          </td>
        </tr>
        <tr>
          <td><Checkbox id="t-2-121" /></td>
          <td>Remedy</td>
          <td><strong><span class="text-category-treasure-chest">Treasure Chest</span></strong></td>
          <td>
            This can be found <strong><em>off the main path in the third area</em></strong>.
          </td>
        </tr>
        <tr>
          <td><Checkbox id="t-2-122" /></td>
          <td>Healing Rod</td>
          <td><strong><span class="text-category-treasure-chest">Treasure Chest</span></strong></td>
          <td>
            This can be found in the <strong
              ><em>second area only after pressing a switch in the third area</em></strong
            >.
          </td>
        </tr>
        <tr>
          <td><Checkbox id="t-2-123" /></td>
          <td>Lamia's Flute</td>
          <td><strong><span class="text-category-treasure-chest">Treasure Chest</span></strong></td>
          <td>
            This can be found <strong><em>off the main path in the third area</em></strong>.
          </td>
        </tr>
        <tr>
          <td><Checkbox id="t-2-124" /></td>
          <td>Brigandine</td>
          <td><strong><span class="text-category-treasure-chest">Treasure Chest</span></strong></td>
          <td>
            This can be found <strong><em>at the bottom of the tree behind a platform</em></strong>.
            It's in the same area where you fight the boss Soulcage.
          </td>
        </tr>
        <tr>
          <td><Checkbox id="t-2-125" /></td>
          <td>Aquamarine</td>
          <td><strong><span class="text-category-story-reward">Story/Reward</span></strong></td>
          <td>This will be given to you by Garnet when she takes it from a statue.</td>
        </tr>
        <tr>
          <td><Checkbox id="t-2-126" /></td>
          <td>Ruby</td>
          <td><strong><span class="text-category-story-reward">Story/Reward</span></strong></td>
          <td>This is given to you after you break the Outer Seal of the Iifa Tree.</td>
        </tr>
      </tbody>
    </table>
  </div>

  <h3 class="text-2xl">Quan's Dwelling (Discs 2, 3, and 4)</h3>

  <div class="rounded-box border-base-content/5 bg-base-100 overflow-x-auto border">
    <table class="table-xs table">
      <colgroup>
        <col style="width: 5%" />
        <col style="width: 20%" />
        <col style="width: 20%" />
        <col style="width: 55%" />
      </colgroup>
      <thead>
        <tr>
          <th></th>
          <th>Item</th>
          <th>Category</th>
          <th>Location</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td><Checkbox id="t-2-127" /></td>
          <td>Ether</td>
          <td><strong><span class="text-category-treasure-chest">Treasure Chest</span></strong></td>
          <td>This can be found on a lone ledge that is above the hot springs.</td>
        </tr>
        <tr>
          <td><Checkbox id="t-2-128" /></td>
          <td>Ether</td>
          <td><strong><span class="text-category-field-icon">Field Icon</span></strong></td>
          <td>
            Inside the "housing" part of the area, this can be found after you have climbed the
            latter.
          </td>
        </tr>
        <tr>
          <td><Checkbox id="t-2-129" /></td>
          <td>Ether</td>
          <td><strong><span class="text-category-treasure-chest">Treasure Chest</span></strong></td>
          <td>This can be found on the shoreline of the hot springs.</td>
        </tr>
        <tr>
          <td><Checkbox id="t-2-130" /></td>
          <td>Running Shoes</td>
          <td><strong><span class="text-category-field-icon">Field Icon</span></strong></td>
          <td>This can be found inside the clock that's on the outside ledge.</td>
        </tr>
        <tr>
          <td><Checkbox id="t-2-131" /></td>
          <td>Scorpio (Stellazio)</td>
          <td><strong><span class="text-category-field-icon">Field Icon</span></strong></td>
          <td>
            Towards the back of the first room, you will notice a hanging rope; slide down said rope
            and make your way towards the bottom of the area. It is located near the hot spring at
            the bottom of the screen boundary.
          </td>
        </tr>
      </tbody>
    </table>
  </div>
</div>
