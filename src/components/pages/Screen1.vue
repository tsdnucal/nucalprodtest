<template>
  <NucGridPage v-bind:gap="{'col':0,'row':0}" v-bind:rows="[1]"
    v-bind:schema="{'r0-c0':{'col':0,'row':0,'showIn':['xs','sm','md','lg'],'colSpan':1,'rowSpan':1}}"
    v-bind:columns="[1]" overflow="auto" v-bind:designMode="false" v-bind:minNsLimit="740"
    v-bind:style="{'background':'#FFFFFF','paddingTop':'0px','paddingLeft':'0px','paddingRight':'0px','paddingBottom':'0px'}">
    <NucGridCell v-bind:wrap="true" v-bind:reverse="false" overflow="hidden" direction="column"
      v-bind:showInDevice="['xs','sm','md','lg']" verticalAlignment="top" horizontalAlignment="left"
      id="bd252ca6-ae24-451c-bab4-cf9c2630ed16" v-bind:col="0" v-bind:row="0" v-bind:colSpan="1" v-bind:rowSpan="1"
      v-bind:marginTop="0" v-bind:marginLeft="0" v-bind:marginRight="0" v-bind:marginBottom="0"
      v-bind:style="{'height':'auto','background':'transparent','paddingTop':'0px','borderColor':'','borderStyle':'solid','borderWidth':'0px','paddingLeft':'0px','borderRadius':'0px','paddingRight':'0px','paddingBottom':'0px','borderTopWidth':'0px','borderLeftWidth':'0px','borderRightWidth':'0px','borderBottomWidth':'0px','borderTopLeftRadius':'1px','borderTopRightRadius':'1px','borderBottomLeftRadius':'1px','borderBottomRightRadius':'1px'}"
      slot="r0-c0" area="r0-c0">
      <WLargeAdvertisement imgSrc="" cardText="Large Rectangle" bgVariant="secondary" textVariant="white"
        v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':false,'structure':[{'type':'string','propName':'imgSrc','displayName':'ImageUrl'},{'type':'string','propName':'cardText','displayName':'Value'}]}"
        verticalPosition="align-items-center" horizontalPosition="justify-content-center" position="absolute"
        top="27.5735950044603%" left="42.299509803921566%" id="b9d14be3-408a-442c-b579-fc6ce9011789"
        v-bind:style="{'width':'','height':'','maxWidth':'','minWidth':'360px','marginTop':'0px','maxHeight':'','minHeight':'350px','marginLeft':'0px','paddingTop':'0px','marginRight':'0px','paddingLeft':'0px','marginBottom':'0px','paddingRight':'0px','paddingBottom':'0px','zIndex':2}"/>
      <WBreadcrumb rel="" href="" icon="house-fill" text="Admin" scale="" shift="" v-bind:active="false"
        v-bind:isIcon="false" v-bind:options="[]" v-bind:disabled="false" v-bind:selected="[]" v-bind:isEnabled="true"
        linkTarget="_self" visibility="visible" ariaCurrent="location" ncTypography="body1" ncTooltipText=""
        v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':false,'structure':[{'type':'string','propName':'text','displayName':'Value'}]}"
        ncClickFontColor="#FFFFFF" ncFocusFontColor="#FFFFFF" ncHoverFontColor="#FFFFFF" ncClickBorderColor="#4285f4"
        ncDisableFontColor="#FFFFFF" ncFocusBorderColor="#4285f4" ncHoverBorderColor="#4285f4"
        ncDisableBorderColor="transparent" ncClickBackgroundColor="#4285f4" ncFocusBackgroundColor="#4285f4"
        ncHoverBackgroundColor="#4285f4" ncDisableBackgroundColor="#969696" position="absolute"
        top="27.396966993755576%" left="25.476960784313725%" id="26988b1b-0b00-4bf1-87a5-0de6ad8a8cfe"
        v-bind:style="{'color':'#007bff','width':'','height':'','fontSize':'16px','maxWidth':'','minWidth':'','fontStyle':'normal','marginTop':'0px','maxHeight':'','minHeight':'','textAlign':'center','background':'#e9ecef','fontFamily':'Roboto-Regular,Roboto','fontWeight':'normal','marginLeft':'0px','paddingTop':'10px','visibility':'visible','marginRight':'0px','paddingLeft':'10px','marginBottom':'0px','paddingRight':'10px','paddingBottom':'10px','textDecoration':'none','zIndex':3}"/>
      <WDateInput id="9800d489-65cb-44d8-a317-a9ab97a88a4f" v-bind:lazy="false" size="md" text="" v-bind:trim="false"
        v-bind:noWheel="false" v-bind:disabled="false" v-bind:readonly="false" v-bind:required="false" wordList=""
        v-bind:autofocus="false" v-bind:plaintext="false" background="" ariaInvalid="false" v-bind:debounceVal="0"
        ncInputType="date" placeholder="" v-bind:previewMode="true" autocomplete="" ncTypography="body1"
        v-bind:lazyFormatter="false" ncTooltipText="" v-bind:isWordListOpen="false"
        v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':true,'structure':[{'type':'string','ncKey':'type','ncType':{'ncInputType':'number'},'ncValue':'number','propName':'text','displayName':'Value','nsDefaultValue':'string'}]}"
        v-bind:isNumberConvert="false" ncClickFontColor="#434855" ncFocusFontColor="#434855" ncHoverFontColor="#434855"
        ncMaxNumberValue="100" ncMinNumberValue="0" ncClickBorderColor="#000000" ncDisableFontColor="#434855"
        ncFocusBorderColor="#000000" ncHoverBorderColor="#000000" ncDisableBorderColor="#000000"
        formatterFunctionName="" ncClickBackgroundColor="#ffffff" ncFocusBackgroundColor="#ffffff"
        ncHoverBackgroundColor="#ffffff" ncDisableBackgroundColor="#ffffff" position="absolute" top="34.70561998215879%"
        left="9.494117647058824%"
        v-bind:style="{'color':'','width':'','height':'','fontSize':'12px','maxWidth':'','minWidth':'','boxShadow':'','fontStyle':'normal','marginTop':'0px','maxHeight':'','minHeight':'','textAlign':'left','fontFamily':'Roboto-Regular,Roboto','fontWeight':'normal','lineHeight':'1','marginLeft':'0px','paddingTop':'0px','visibility':'visible','borderColor':'#D1D1D6','borderStyle':'solid','marginRight':'0px','paddingLeft':'0px','marginBottom':'0px','paddingRight':'0px','paddingBottom':'0px','textDecoration':'none','zIndex':4}"/>
      <WButtonCheckbox size="sm" label="Button Check" v-bind:plain="false" theme="theme--light01" v-bind:value="false"
        v-bind:button="true" v-bind:inline="false" fontSize="14px" v-bind:autofocus="false" v-bind:isEnabled="true"
        textAlign="left" fontFamily="Roboto-Regular,Roboto" fontWeight="normal" ncTypography="custom"
        v-bind:indeterminate="false" labelPosition="right" ncTooltipText="" v-bind:checkboxSwitch="false"
        v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':false,'structure':[{'type':'boolean','propName':'value','displayName':'Value'},{'type':'string','propName':'label','displayName':'Display'}]}"
        ncFocusFontColor="black" ncHoverFontColor="black" ncDisableFontColor="black" ncFocusBorderColor="black"
        ncHoverBorderColor="black" ncDisableBorderColor="black" ncFocusBackgroundColor="transparent"
        ncHoverBackgroundColor="transparent" ncDisableBackgroundColor="transparent" position="absolute"
        top="59.905660377358494%" left="35.14705882352941%" v-bind:snapX="false" v-bind:snapY="false"
        id="1ae71b97-803d-41ff-abe1-f1ac408f65c7"
        v-bind:style="{'color':'','width':'','height':'','maxWidth':'','minWidth':'','tabIndex':'0px','boxShadow':'','fontStyle':'none','marginTop':'0px','maxHeight':'','minHeight':'','lineHeight':'','marginLeft':'0px','paddingTop':'0px','textShadow':'','visibility':'visible','marginRight':'0px','paddingLeft':'0px','marginBottom':'0px','paddingRight':'0px','paddingBottom':'0px','textDecoration':'none','zIndex':5}"/>
      <WSmallCheckbox size="sm" label="Small" v-bind:plain="false" theme="theme--light01" v-bind:value="true"
        v-bind:inline="false" fontSize="14px" v-bind:autofocus="false" v-bind:isEnabled="true" textAlign="left"
        fontFamily="Roboto-Regular,Roboto" fontWeight="normal" ncTypography="custom" v-bind:indeterminate="false"
        labelPosition="right" ncTooltipText="" v-bind:checkboxSwitch="false"
        v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':false,'structure':[{'type':'boolean','propName':'value','displayName':'Value'},{'type':'string','propName':'label','displayName':'Display'}]}"
        ncFocusFontColor="black" ncHoverFontColor="black" ncDisableFontColor="black" ncFocusBorderColor="black"
        ncHoverBorderColor="black" ncDisableBorderColor="black" ncFocusBackgroundColor="transparent"
        ncHoverBackgroundColor="transparent" ncDisableBackgroundColor="transparent" position="absolute"
        top="76.021409455843%" left="20.662254901960786%" id="1939310e-20d1-4873-92b1-e226a8791719"
        v-bind:style="{'color':'','width':'','height':'','maxWidth':'','minWidth':'','tabIndex':'0px','boxShadow':'','fontStyle':'none','marginTop':'0px','maxHeight':'','minHeight':'','lineHeight':'','marginLeft':'0px','paddingTop':'0px','textShadow':'','visibility':'visible','marginRight':'0px','paddingLeft':'0px','marginBottom':'0px','paddingRight':'0px','paddingBottom':'0px','textDecoration':'none','zIndex':6}"/>
      <NucCheckbox label="Checkbox" theme="theme--light01" v-bind:value="true" fontSize="14px" v-bind:isEnabled="true"
        textAlign="left" fontFamily="Roboto-Regular,Roboto" fontWeight="normal" ncTypography="custom"
        labelPosition="right" ncTooltipText=""
        v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':false,'structure':[{'type':'boolean','propName':'value','displayName':'Value'},{'type':'string','propName':'label','displayName':'Display'}]}"
        ncFocusFontColor="black" ncHoverFontColor="black" ncDisableFontColor="black" ncFocusBorderColor="black"
        ncHoverBorderColor="black" ncDisableBorderColor="black" ncFocusBackgroundColor="transparent"
        ncHoverBackgroundColor="transparent" ncDisableBackgroundColor="transparent" position="absolute"
        top="72.97056199821589%" left="34.43186274509804%" id="ce9ee5ba-c0d4-463a-917d-c0f101a9f340"
        v-bind:style="{'color':'','width':'100','height':'','maxWidth':'','minWidth':'','tabIndex':'0px','boxShadow':'','fontStyle':'none','marginTop':'0px','maxHeight':'','minHeight':'','lineHeight':'1','marginLeft':'0px','paddingTop':'2px','textShadow':'','visibility':'visible','marginRight':'0px','paddingLeft':'2px','marginBottom':'0px','paddingRight':'2px','paddingBottom':'2px','textDecoration':'none','zIndex':7}"/>
      <WColorInput id="a1ca2693-0d32-484c-8614-9565d86778ac" v-bind:lazy="false" size="md" step="" text=""
        v-bind:trim="false" v-bind:noWheel="false" v-bind:disabled="false" v-bind:readonly="false"
        v-bind:required="false" wordList="" v-bind:autofocus="false" v-bind:plaintext="false" background=""
        ariaInvalid="false" v-bind:debounceVal="0" ncInputType="color" placeholder="" v-bind:previewMode="true"
        autocomplete="" ncTypography="body1" v-bind:lazyFormatter="false" ncTooltipText="" v-bind:isWordListOpen="false"
        v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':true,'structure':[{'type':'string','ncKey':'type','ncType':{'ncInputType':'number'},'ncValue':'number','propName':'text','displayName':'Value','nsDefaultValue':'string'}]}"
        v-bind:isNumberConvert="false" ncClickFontColor="#434855" ncFocusFontColor="#434855" ncHoverFontColor="#434855"
        ncMaxNumberValue="100" ncMinNumberValue="0" ncClickBorderColor="#000000" ncDisableFontColor="#434855"
        ncFocusBorderColor="#000000" ncHoverBorderColor="#000000" ncDisableBorderColor="#000000"
        formatterFunctionName="" ncClickBackgroundColor="#ffffff" ncFocusBackgroundColor="#ffffff"
        ncHoverBackgroundColor="#ffffff" ncDisableBackgroundColor="#ffffff" position="absolute" top="85.02943800178411%"
        left="22.312254901960785%"
        v-bind:style="{'color':'','width':'','height':'','fontSize':'12px','maxWidth':'','minWidth':'158px','boxShadow':'','fontStyle':'normal','marginTop':'0px','maxHeight':'','minHeight':'','textAlign':'left','fontFamily':'Roboto-Regular,Roboto','fontWeight':'normal','lineHeight':'1','marginLeft':'0px','paddingTop':'0px','visibility':'visible','borderColor':'#D1D1D6','borderStyle':'solid','marginRight':'0px','paddingLeft':'0px','marginBottom':'0px','paddingRight':'0px','paddingBottom':'0px','textDecoration':'none','zIndex':8}"/>
      <TwCombobox v-bind:options="[]" v-bind:selected="[]" dataModel="" headerText="Combobox" dataLoading=""
        headerColor="tw-text-gray-700" placeholder="Please select an option" dataModelType="" ncTooltipText=""
        headerFontSize="tw-text-lg" itemHoverColor="tw-bg-indigo-600"
        v-bind:nucalDataModel="{'type':'NSW','isList':true,'update':{'dataModel':'dataModel'},'dynamic':true,'structure':[{'update':{'type':'dataModelType','dataModel':'dataModel'},'propName':'options','displayName':'Value'}]}"
        headerFontFamily="tw-font-sans" headerFontWeight="tw-font-medium" position="absolute" top="44.17216770740411%"
        left="20.224509803921567%" id="627f7faa-69b3-4d9f-8bd6-4f0bfe2c385b"
        v-bind:style="{'width':'740','height':'121','maxWidth':'','minWidth':'','marginTop':'0px','maxHeight':'','minHeight':'','marginLeft':'0px','paddingTop':'10px','visibility':'visible','marginRight':'0px','paddingLeft':'10px','marginBottom':'0px','paddingRight':'0px','paddingBottom':'0px','zIndex':9}"/>
      <WCopy id="02b5a692-348c-41e7-828c-bce405ab11a6" v-bind:lazy="false" size="md" step="" text="" v-bind:trim="false"
        v-bind:noWheel="false" v-bind:disabled="false" v-bind:readonly="false" v-bind:required="false" wordList=""
        v-bind:autofocus="false" v-bind:plaintext="false" background="" ariaInvalid="false" v-bind:debounceVal="0"
        ncInputType="text" placeholder="Enter something..." v-bind:previewMode="true" autocomplete=""
        ncTypography="body1" v-bind:lazyFormatter="false" ncTooltipText="" v-bind:isWordListOpen="false"
        v-bind:isNumberConvert="false" ncClickFontColor="#434855" ncFocusFontColor="#434855" ncHoverFontColor="#434855"
        ncMaxNumberValue="100" ncMinNumberValue="0" ncClickBorderColor="#000000" ncDisableFontColor="#434855"
        ncFocusBorderColor="#000000" ncHoverBorderColor="#000000" ncDisableBorderColor="#000000"
        formatterFunctionName="" ncClickBackgroundColor="#ffffff" ncFocusBackgroundColor="#ffffff"
        ncHoverBackgroundColor="#ffffff" ncDisableBackgroundColor="#ffffff" position="absolute" top="71.38269402319358%"
        left="69.69411764705882%"
        v-bind:style="{'width':'','height':'','fontSize':'12px','maxWidth':'','minWidth':'170px','boxShadow':'','fontStyle':'normal','marginTop':'0px','maxHeight':'','minHeight':'','fontFamily':'Roboto-Regular,Roboto','fontWeight':'normal','lineHeight':'1','marginLeft':'0px','paddingTop':'0px','visibility':'visible','marginRight':'0px','paddingLeft':'0px','marginBottom':'0px','paddingRight':'0px','paddingBottom':'0px','textDecoration':'none','zIndex':10}"/>
      <WDatatable v-bind:list="[]" type="" theme="theme--light01" v-bind:isDark="false" v-bind:columns="[]"
        v-bind:hasSort="false" v-bind:isFixed="false" parject="" v-bind:perPage="5" dataModel=""
        v-bind:hasFilter="false" v-bind:hasSearch="false" v-bind:isStriped="false" v-bind:extensions="{}"
        v-bind:isBordered="true" v-bind:isOutlined="false" selectMode="single" v-bind:currentPage="1" footVariant=""
        headVariant="" v-bind:isFootClone="false" v-bind:isBorderless="false" v-bind:isCaptionTop="false"
        v-bind:isResponsive="false" v-bind:isSelectable="false" ncTypography="body2" v-bind:selectedRows="[]"
        tableVariant="" v-bind:hasPagination="false" sortDirection="" v-bind:isStickyHeader="false"
        v-bind:nucalDataModel="{'type':'NSW','isList':true,'update':{'dataModel':'dataModel'},'dynamic':true,'structure':[{'type':'ids-list','update':{'dataModel':'dataModel'},'propName':'selectedRows','displayName':'SelectedRows'},{'type':'ids-list','update':{'dataModel':'dataModel'},'propName':'list','displayName':'List'}]}"
        v-bind:smallSelection="false" v-bind:isNoFooterSorting="false" v-bind:isNoBorderCollapse="false"
        position="absolute" top="0%" left="76.42156862745098%" v-bind:snapX="false" v-bind:snapY="false"
        id="9f10b285-0649-4f9c-a538-b0f49485fc95"
        v-bind:style="{'color':'#475562','fontSize':'11px','maxWidth':'','minWidth':'300px','fontStyle':'normal','marginTop':'0px','maxHeight':'','minHeight':'100px','textAlign':'left','fontFamily':'Roboto-Regular,Roboto','fontWeight':'normal','marginLeft':'0px','paddingTop':'12px','visibility':'visible','marginRight':'0px','paddingLeft':'13px','marginBottom':'0px','paddingRight':'13px','paddingBottom':'12px','textDecoration':'none','zIndex':11}"/>
      <NucDataTable v-bind:list="[]" type="" theme="theme--light01" v-bind:columns="[]" parject="" dataModel=""
        bindMethod="function" v-bind:extensions="{}" ncTypography="body2" v-bind:selectedRows="[]"
        v-bind:nucalDataModel="{'type':'NSW','isList':true,'update':{'dataModel':'dataModel'},'dynamic':true,'structure':[{'type':'ids-list','update':{'dataModel':'dataModel'},'propName':'selectedRows','displayName':'SelectedRows'},{'type':'ids-list','update':{'dataModel':'dataModel'},'propName':'list','displayName':'List'}]}"
        v-bind:specialEventList="[]" position="absolute" top="25.517395182872434%" left="74.2985294117647%"
        id="9f3598c1-5e91-420c-be4f-e4c3bf0d342e"
        v-bind:style="{'color':'#475562','width':'','height':'','fontSize':'11px','maxWidth':'','minWidth':'300px','fontStyle':'normal','marginTop':'0px','maxHeight':'','minHeight':'100px','textAlign':'left','fontFamily':'Roboto-Regular,Roboto','fontWeight':'normal','marginLeft':'0px','paddingTop':'12px','visibility':'visible','marginRight':'0px','paddingLeft':'13px','marginBottom':'0px','paddingRight':'13px','paddingBottom':'12px','textDecoration':'none','zIndex':12}"/>
    </NucGridCell>
  </NucGridPage>
</template>
<script>
export default {
  name: 'Screen1',
  data() {
    return {};
  },
  props: {},
  created() {},
  mounted() {},
  computed: {},
  methods: {},
  watch: {},
};
</script>

<style scoped></style>