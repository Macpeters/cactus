<template>
  <div>
    <img v-bind:src="image"  />

    <article>
      <h2>Notes on the species</h2>
      <div>
        They seem to have a fairly good germ rate, and are quick to show it.  All my seeds so far have been purchased
        from Sacred Seed in Toronto 
        <div>
          <h3>Varieties</h3>
          <ul>
            <li><strong>Caespitosa</strong>: will easily grow multiple heads without any decapitation happening.  This makes them very easy
            to propogate.  These head form large clusters known as 'planchas'</li>
            <li><strong>Menchaka</strong>: tend to have only one head, unless decapitation occurs.</li>
          </ul>
        </div>
      </div>
    </article>

    <article>
      <h2>Batch 3: v caespitosa</h2>
      <div>
        <h3>Sowing the seeds: 05/2019</h3>
          <div>100 seeds - 3 X 2 inch plastic pots in a plastic bin with lid</div>
      </div>
      <div>
        <h3>Seedlings</h3>
          <div>
            It looks like about 64 have germinated.  I can't get an exact count because of the way they're scattered, and it looks like a few more 
            are trying to put down roots.  We'll see what happens.
          </div>
      </div>
    </article>
    
     <article>
      <h2>Batch 2: v caespitosa</h2>
      <div>
        <h3>Sowing the seeds: 03/2019</h3>
          <div>20 seeds - a 2 inch plastic pot in a baggy</div>
      </div>
      <div>
        <h3>Seedlings</h3>
          <div>
            15 seedlings remain as of 05/2019.  They are bright green and lush.  A couple are oddly shaped.  I am currenly using an LED grow light,
            and I am considering whether or not flourescent might be a better option in general, although I worry it might be too much for seedlings.
            These ones seem happy enough and I don't really want to mess with that.  They'll be in plastic for a few more months, all going well.
          </div>
      </div>
    </article>

    <article>
      <h2>Batch 1: v caespitosa</h2>
      <div>
        <h3>Sowing the seeds: 09/2018</h3>
          <div>30 seeds - half in a plastic icecube tray with a plastic cover and half in a 2 inch clay pot in a baggy</div>
      </div>
      <div>
        <h3>Seedlings</h3>
          <div>
            16 seedlings remain as of 05/2019.  Many are misshapen and odd looking.  I took the seedlings out of plastic much earlier
            than I needed to and they seem small and stunted compared to other seedlings which were planted later.  They are alive, though.
            The ones in the icecube tray had a much better germination rate.  There were some redish tinges for a little while, and I experimented 
            with moving the seedlings further from the light, which led to yellowing and stretching.  They seem stable enough now - dark green, 
            hardened, and under flourescent light.  My only flor light is 24 hrs.  <strong>Do cacti need to sleep?</strong>
          </div>
      </div>
    </article>

    <article>
      <h2>Charlie: v menchaka</h2>
      <div>
        <h3>Born November 6, 2014</h3>
          <div>
            This is one of the only cacti I own that I didn't plant. He was 2.5 years old when I picked him up (Spring 2018-ish).  
            Still quite small, as these fellas tend to be, but seems happy enough.  I moved him from his tiny plastic pot to a 
            slightly larger clay pot. 
          </div>
      </div>
    </article>
  </div>
</template>

<script>
  import image from '../../assets/cacti/lopophoraWilliamsii.jpg';

  export default {
    head () {
      return {
        name: 'lopophoraWilliamsii',
        title: 'Lopophora williamsii',
        meta: [
          { hid: 'description', name: 'description', content: 'Lopophora grow log' }
        ]
      }
    },
    data() {
      return {
        image
      };
    }
  }
</script>

<style lang="css" src="./logs.css" scoped></style>
