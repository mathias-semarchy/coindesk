<?xml version="1.0" encoding="UTF-8"?>
<md:node xmlns:md="http://www.stambia.com/md" defType="com.stambia.http.rest" id="_V28Z8H_TEe66k6FTAcuvzA" name="coindesk" md:ref="resource.tech#UUID_TECH_HTTPREST?fileId=UUID_TECH_HTTPREST$type=tech$name=HttpRest?" internalVersion="v2.0.0">
  <attribute defType="com.stambia.http.rest.module" id="_V3Fj4H_TEe66k6FTAcuvzA" value="HttpRest"/>
  <attribute defType="com.stambia.http.rest.url" id="_di_foH_TEe66k6FTAcuvzA" value="https://api.coindesk.com/v1/bpi/"/>
  <node defType="com.stambia.http.rest.path" id="_WzzDwH_TEe66k6FTAcuvzA">
    <attribute defType="com.stambia.http.rest.path.path" id="_gSDG4H_TEe66k6FTAcuvzA" value="currentprice.json"/>
    <node defType="com.stambia.http.rest.operation" id="_gGFHcX_TEe66k6FTAcuvzA">
      <attribute defType="com.stambia.http.rest.operation.method" id="_hKRvYH_TEe66k6FTAcuvzA" value="GET"/>
      <node defType="com.stambia.http.rest.responses" id="_lsDRd3_TEe66k6FTAcuvzA">
        <node defType="com.stambia.http.rest.response" id="_lsDReH_TEe66k6FTAcuvzA">
          <attribute defType="com.stambia.http.rest.response.code" id="_lsDReX_TEe66k6FTAcuvzA" value="200"/>
          <node defType="com.stambia.http.rest.headers" id="_lsDRen_TEe66k6FTAcuvzA">
            <node defType="com.stambia.http.rest.header" id="_lsDRe3_TEe66k6FTAcuvzA" name="X-Cache"/>
            <node defType="com.stambia.http.rest.header" id="_lsDRfH_TEe66k6FTAcuvzA" name="Server"/>
            <node defType="com.stambia.http.rest.header" id="_lsDRfX_TEe66k6FTAcuvzA" name="Access-Control-Allow-Origin"/>
            <node defType="com.stambia.http.rest.header" id="_lsDRfn_TEe66k6FTAcuvzA" name="X-Amz-Cf-Pop"/>
            <node defType="com.stambia.http.rest.header" id="_lsDRf3_TEe66k6FTAcuvzA" name="Connection"/>
            <node defType="com.stambia.http.rest.header" id="_lsDRgH_TEe66k6FTAcuvzA" name="Date"/>
            <node defType="com.stambia.http.rest.header" id="_lsDRgX_TEe66k6FTAcuvzA" name="Via"/>
            <node defType="com.stambia.http.rest.header" id="_lsDRgn_TEe66k6FTAcuvzA" name="Cache-Control"/>
            <node defType="com.stambia.http.rest.header" id="_lsDRg3_TEe66k6FTAcuvzA" name="X-Amz-Cf-Id"/>
            <node defType="com.stambia.http.rest.header" id="_lsDRhH_TEe66k6FTAcuvzA" name="Expires"/>
            <node defType="com.stambia.http.rest.header" id="_lsDRhX_TEe66k6FTAcuvzA" name="Content-Length"/>
            <node defType="com.stambia.http.rest.header" id="_lsDRhn_TEe66k6FTAcuvzA" name="Age"/>
            <node defType="com.stambia.http.rest.header" id="_lsDRh3_TEe66k6FTAcuvzA" name="Content-Type"/>
            <node defType="com.stambia.http.rest.header" id="_lsDRiH_TEe66k6FTAcuvzA" name="X-Powered-By"/>
          </node>
          <node defType="com.stambia.http.rest.content" id="_lsDRiX_TEe66k6FTAcuvzA">
            <attribute defType="com.stambia.http.rest.content.mediaType" id="_lsDRin_TEe66k6FTAcuvzA" value="JSON"/>
            <attribute defType="com.stambia.http.rest.content.contentType" id="_lsDRi3_TEe66k6FTAcuvzA" value="application/javascript"/>
            <node defType="com.stambia.json.rootObject" id="_lsDRjH_TEe66k6FTAcuvzA" name="root">
              <node defType="com.stambia.json.value" id="_lsDRjX_TEe66k6FTAcuvzA" name="chartName" position="3">
                <attribute defType="com.stambia.json.value.type" id="_lsDRjn_TEe66k6FTAcuvzA" value="string"/>
              </node>
              <node defType="com.stambia.json.value" id="_lsDRj3_TEe66k6FTAcuvzA" name="disclaimer" position="2">
                <attribute defType="com.stambia.json.value.type" id="_lsDRkH_TEe66k6FTAcuvzA" value="string"/>
              </node>
              <node defType="com.stambia.json.object" id="_lsDRkX_TEe66k6FTAcuvzA" name="bpi" position="4">
                <node defType="com.stambia.json.object" id="_lsDRkn_TEe66k6FTAcuvzA" name="USD" position="1">
                  <node defType="com.stambia.json.value" id="_lsDRk3_TEe66k6FTAcuvzA" name="code" position="1">
                    <attribute defType="com.stambia.json.value.type" id="_lsDRlH_TEe66k6FTAcuvzA" value="string"/>
                  </node>
                  <node defType="com.stambia.json.value" id="_lsDRlX_TEe66k6FTAcuvzA" name="symbol" position="2">
                    <attribute defType="com.stambia.json.value.type" id="_lsDRln_TEe66k6FTAcuvzA" value="string"/>
                  </node>
                  <node defType="com.stambia.json.value" id="_lsDRl3_TEe66k6FTAcuvzA" name="rate" position="3">
                    <attribute defType="com.stambia.json.value.type" id="_lsDRmH_TEe66k6FTAcuvzA" value="string"/>
                  </node>
                  <node defType="com.stambia.json.value" id="_lsDRmX_TEe66k6FTAcuvzA" name="description" position="4">
                    <attribute defType="com.stambia.json.value.type" id="_lsDRmn_TEe66k6FTAcuvzA" value="string"/>
                  </node>
                  <node defType="com.stambia.json.value" id="_lsDRm3_TEe66k6FTAcuvzA" name="rate_float" position="5">
                    <attribute defType="com.stambia.json.value.type" id="_lsDRnH_TEe66k6FTAcuvzA" value="number"/>
                  </node>
                </node>
                <node defType="com.stambia.json.object" id="_lsDRnX_TEe66k6FTAcuvzA" name="GBP" position="2">
                  <node defType="com.stambia.json.value" id="_lsDRnn_TEe66k6FTAcuvzA" name="code" position="1">
                    <attribute defType="com.stambia.json.value.type" id="_lsDRn3_TEe66k6FTAcuvzA" value="string"/>
                  </node>
                  <node defType="com.stambia.json.value" id="_lsDRoH_TEe66k6FTAcuvzA" name="symbol" position="2">
                    <attribute defType="com.stambia.json.value.type" id="_lsDRoX_TEe66k6FTAcuvzA" value="string"/>
                  </node>
                  <node defType="com.stambia.json.value" id="_lsDRon_TEe66k6FTAcuvzA" name="rate" position="3">
                    <attribute defType="com.stambia.json.value.type" id="_lsDRo3_TEe66k6FTAcuvzA" value="string"/>
                  </node>
                  <node defType="com.stambia.json.value" id="_lsDRpH_TEe66k6FTAcuvzA" name="description" position="4">
                    <attribute defType="com.stambia.json.value.type" id="_lsDRpX_TEe66k6FTAcuvzA" value="string"/>
                  </node>
                  <node defType="com.stambia.json.value" id="_lsDRpn_TEe66k6FTAcuvzA" name="rate_float" position="5">
                    <attribute defType="com.stambia.json.value.type" id="_lsDRp3_TEe66k6FTAcuvzA" value="number"/>
                  </node>
                </node>
                <node defType="com.stambia.json.object" id="_lsDRqH_TEe66k6FTAcuvzA" name="EUR" position="3">
                  <node defType="com.stambia.json.value" id="_lsDRqX_TEe66k6FTAcuvzA" name="code" position="1">
                    <attribute defType="com.stambia.json.value.type" id="_lsDRqn_TEe66k6FTAcuvzA" value="string"/>
                  </node>
                  <node defType="com.stambia.json.value" id="_lsDRq3_TEe66k6FTAcuvzA" name="symbol" position="2">
                    <attribute defType="com.stambia.json.value.type" id="_lsDRrH_TEe66k6FTAcuvzA" value="string"/>
                  </node>
                  <node defType="com.stambia.json.value" id="_lsDRrX_TEe66k6FTAcuvzA" name="rate" position="3">
                    <attribute defType="com.stambia.json.value.type" id="_lsDRrn_TEe66k6FTAcuvzA" value="string"/>
                  </node>
                  <node defType="com.stambia.json.value" id="_lsDRr3_TEe66k6FTAcuvzA" name="description" position="4">
                    <attribute defType="com.stambia.json.value.type" id="_lsDRsH_TEe66k6FTAcuvzA" value="string"/>
                  </node>
                  <node defType="com.stambia.json.value" id="_lsDRsX_TEe66k6FTAcuvzA" name="rate_float" position="5">
                    <attribute defType="com.stambia.json.value.type" id="_lsDRsn_TEe66k6FTAcuvzA" value="number"/>
                  </node>
                </node>
              </node>
              <node defType="com.stambia.json.object" id="_lsDRs3_TEe66k6FTAcuvzA" name="time" position="1">
                <node defType="com.stambia.json.value" id="_lsDRtH_TEe66k6FTAcuvzA" name="updated" position="1">
                  <attribute defType="com.stambia.json.value.type" id="_lsDRtX_TEe66k6FTAcuvzA" value="string"/>
                </node>
                <node defType="com.stambia.json.value" id="_lsDRtn_TEe66k6FTAcuvzA" name="updatedISO" position="2">
                  <attribute defType="com.stambia.json.value.type" id="_lsDRt3_TEe66k6FTAcuvzA" value="string"/>
                </node>
                <node defType="com.stambia.json.value" id="_lsDRuH_TEe66k6FTAcuvzA" name="updateduk" position="3">
                  <attribute defType="com.stambia.json.value.type" id="_lsDRuX_TEe66k6FTAcuvzA" value="string"/>
                </node>
              </node>
            </node>
          </node>
        </node>
      </node>
    </node>
  </node>
</md:node>