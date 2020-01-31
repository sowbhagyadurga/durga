**1.Get Orders:**

**API URL:**  http://13.57.137.152:5005/0x/v2/orders

**Method Type:** Get

**InputJson:**

input query parameters: page,perPage

ex: ox/v2/orders?page=2&amp;perPage=5

**2.Get Order:**

**API URL:**  http://13.57.137.152:5005/0x/v2/order/:orderhash

**Method Type:** Get

**InputJson:**

Ex: ox/v2/order/0x84e480346c591a2bc690360c265645da526cd75bce6046e26442b2a8d1a3e892

**3.Get Orderbook**

**API URL:** http://13.57.137.152:5005/0x/v2/getOrderbook

**Method Type:** Get

**InputJson:**

input query parameters :baseAssetData,quoteAssetData,networkId,page,perPage

**ex:**

ox/v2/getOrderbook?baseassetdata=0xf47261b0000000000000000000000000e41d2489571d322189246dafa5ebde1f4699f498&amp;quoteassetdata=0x02571792000000000000000000000000371b13d97f4bf77d724e78c16b7dc74099f40e840000000000000000000000000000000000000000000000000000000000000063

**4.Get OrderConfig**

**API URL** : http://13.57.137.152:5005/0x/v2/getOrderConfig

**Method Type:** POST

**InputJson:**

{

  &quot;makerAddress&quot;: &quot;0x2002d3812f58e35f0ea1ffbf80a75a38c32175fa&quot;,

  &quot;takerAddress&quot;: &quot;0xd0a1e359811322d97991e03f863a0c30c2cf029c&quot;,

  &quot;makerAssetAmount&quot;: 32000000000000,

  &quot;takerAssetAmount&quot;: 200000000000000,

  &quot;makerAssetData&quot;: &quot;0x02571792000000000000000000000000371b13d97f4bf77d724e78c16b7dc74099f40e840000000000000000000000000000000000000000000000000000000000000063&quot;,

  &quot;takerAssetData&quot;: &quot;0xf47261b0000000000000000000000000e41d2489571d322189246dafa5ebde1f4699f498&quot;,

  &quot;exchangeAddress&quot;: &quot;0x90fe2af704b34e0224bf2299c838e04d4dcf1364&quot;,

  &quot;expirationTimeSeconds&quot;: 1537513423909

}

**5.FeeRecipients**

**API URL:** http://13.57.137.152:5005/0x/v2/fee\_recipients

**Method Type:** Get

**InputJson:**

input query parameters: page,perPage

**ex:** ox/v2/fee\_recipients?page=2&amp;perPage=5

**6.PostOrder**

**API URL:** http://13.57.137.152:5005/0x/v2/postOrder

**Method Type:** Post

**InputJson:**

{

  &quot;makerAddress&quot;: &quot;0x9e56625509c2f60af937f23b7b532600390e8c8b&quot;,

  &quot;takerAddress&quot;: &quot;0xa2b31dacf30a9c50ca473337c01d8a201ae33e32&quot;,

  &quot;feeRecipientAddress&quot;: &quot;0xb046140686d052fff581f63f8136cce132e857da&quot;,

  &quot;senderAddress&quot;: &quot;0xa2b31dacf30a9c50ca473337c01d8a201ae33e32&quot;,

  &quot;makerAssetAmount&quot;: &quot;10000000000000000&quot;,

  &quot;takerAssetAmount&quot;: &quot;20000000000000000&quot;,

  &quot;makerFee&quot;: &quot;100000000000000&quot;,

  &quot;takerFee&quot;: &quot;200000000000000&quot;,

  &quot;expirationTimeSeconds&quot;: &quot;1532560590&quot;,

  &quot;salt&quot;: &quot;1532559225&quot;,

  &quot;makerAssetData&quot;: &quot;0xf47261b0000000000000000000000000e41d2489571d322189246dafa5ebde1f4699f498&quot;,

  &quot;takerAssetData&quot;: &quot;0x02571792000000000000000000000000371b13d97f4bf77d724e78c16b7dc74099f40e840000000000000000000000000000000000000000000000000000000000000063&quot;,

  &quot;exchangeAddress&quot;: &quot;0x12459c951127e0c374ff9105dda097662a027093&quot;,

  &quot;signature&quot;: &quot;0x012761a3ed31b43c8780e905a260a35faefcc527be7516aa11c0256729b5b351bc33&quot;
  data add in;

}
