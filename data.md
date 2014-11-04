Haiti - Big Aid

{ "_id" : ObjectId("5451bd00812a06a90b579103"), "recipient" : "Haiti", "disburse
ment_amount" : NumberLong(377682000) }
> db.aiddata.find({"disbursement_amount" : {$gt : 100000000}, "recipient":"Haiti
"},{}).sort({"disbursement_amount" : -1})
{ "_id" : ObjectId("5451bd00812a06a90b579103"), "aiddata_id" : NumberLong(980886
69), "year" : 2010, "commitment_date" : "", "start_date" : "2010-01-01 00:00:00"
, "end_date" : "2010-12-31 00:00:00", "donor" : "United States", "donor_iso2" :
"US", "donor_iso3" : "USA", "umbrella" : "", "donor_project_id" : "DHA09999", "c
rsid" : NumberLong(2010049098), "financing_agency" : "DOD", "donor_type" : "Bila
teral", "bi_multi" : 1, "recipient" : "Haiti", "recipient_iso2" : "HT", "recipie
nt_iso3" : "HTI", "private_recipient" : "", "implementing_agency" : "Organisatio
n of American States", "channel_code" : "", "borrower" : "", "beneficiary" : "",
 "guarantor" : "", "other_involved_institutions" : "", "commitment_amount" : Num
berLong(421543000), "commitment_amount_currency" : "USD", "commitment_amount_usd
_nominal" : NumberLong(421543000), "commitment_amount_usd_constant" : 417315423.
659011, "disbursement_amount" : NumberLong(377682000), "disbursement_amount_curr
ency" : "USD", "disbursement_amount_usd_nominal" : NumberLong(377682000), "disbu
rsement_amount_usd_constant" : 373894297.469967, "total_project_cost" : "", "tot
al_project_cost_currency" : "", "total_project_cost_usd_nominal" : "", "total_pr
oject_cost_usd_constant" : "", "title" : "Humanitarian Assistance", "short_descr
iption" : "HUMANITARIAN ASSISTANCE", "short_description_original_language" : "",
 "long_description" : "Humanitarian Assistance", "long_description_original_lang
uage" : "", "additional_info" : "", "additional_info_original_language" : "", "f
low_type" : "ODA Grants", "crs_flow_name" : "ODA Grants", "number_repayments_per
_year" : "", "repay_type" : "", "loan_term" : "", "grace_period" : "", "interest
_rate" : "", "second_interest_rate" : "", "grant_element" : 100, "cancelled" : "
", "repay_date_first" : "", "repay_date_last" : "", "untied_amount_usd_nominal"
: "", "partial_tied_amount_usd_nominal" : "", "tied_amount_usd_nominal" : 421.54
3, "received_amount_usd_nominal" : "", "irtc_amount_usd_nominal" : "", "expert_c
ommitment_amount_usd_nominal" : "", "expert_extended_amount_usd_nominal" : "", "
export_credit_amount_usd_nominal" : "", "outstanding_amount_usd_nominal" : "", "
arrears_principal_amount_usd_nominal" : "", "arrears_interest_amount_usd_nominal
" : "", "future_ds_principal_amount_usd_nominal" : "", "future_ds_interest_amoun
t_usd_nominal" : "", "region" : "North & Central America", "location" : "", "sou
rce" : "OECD CRS", "language" : "English", "biodiversity" : 0, "climate" : 0, "d
esertification" : 0, "crs_purpose_code" : 72010, "crs_purpose_name" : "Emergency
/distress relief", "gender" : "", "trade" : 0, "pdgg" : 0, "ftc" : "", "sector_p
rogramme" : "", "sector" : "VIII.1. Emergency Response", "sector_code" : 720, "a
ssociated_financing" : "", "initial_report" : 1, "finance_t" : 110, "environment
al_impact_assessment" : "", "environment" : 0, "investment_project" : "", "aidda
ta_purpose_code" : "", "aiddata_purpose_name" : "", "aiddata_activity_code" : ""
, "aiddata_activity_name" : "", "aiddata_feasibility_study" : "", "aiddata_techn
ical_assistance" : "", "coalesced_purpose_code" : 72010, "coalesced_purpose_name
" : "Emergency/distress relief" }